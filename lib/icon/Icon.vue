<template>
    <svg class="v-icon" aria-hidden="true">
        <use :xlink:href="`#i-${icon}`"></use>
    </svg>
</template>

<script>
import './svg';

export default {
    name: 'v-icon',
    props: ['icon']
}
</script>

<style lang="scss">
.v-icon {
    width: 14px;
    height: 14px;
    fill: currentColor;
}
</style>
