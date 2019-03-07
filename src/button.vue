<template>
    <button class="g-button">按钮</button>
</template>

<script>
    export default {

    }
</script>

<style lang="scss">
    .g-button{
        font-size: var(--font-size);
        height: var(--button-height);
        color: var(--color);
        padding: 0 1em;
        background: var(--button-bg);
        border: 1px solid var(--border-colr);
        border-radius: var(--border-radius);
        outline: none;
        cursor: pointer;
        &:hover{
            border-color: var(--border-color-hover);
        }
        &:active{
            background-color: var(--button-active-bg);
        }
    }

</style>