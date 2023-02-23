<page>
    <actionBar title="Home" />
    <gridLayout>
        <MyText text="hello" />
    </gridLayout>
</page>

<script lang="ts">
    import { MyText } from 'gb7sveltelib';

    let message: string = "Blank Svelte Native App"
</script>

<style>
    .info .fas {
        color: #3A53FF;
    }

    .info {
        font-size: 20;
        horizontal-align: center;
        vertical-align: center;
    }
</style>
