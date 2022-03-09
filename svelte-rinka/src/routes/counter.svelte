<!-- JavaScript -->
<script lang="ts">
    // 変数宣言　数値型　最初は０を入れる
    let count: number = 0;  // 数値
    let name: string = "rinka"; // 文字列

    // さっきの変数に１プラスする変数を入れる
    const clickHandler = () => {
        count++;    // インクリメント
        console.log(count);
    }
    
    const clickHandler2 = () => {
        count--;    // デクリメント
        console.log(count);
    }
</script>

<!-- html -->
<body>
    <h1>{name}</h1>
    
    {count}

    <button on:click={clickHandler}>
        <p>＋</p>
    </button>

    <button on:click={clickHandler2}>
        <p>ー</p>
    </button>
</body>

<!-- css -->
<style>

</style>