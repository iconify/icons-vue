<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zoie8jzjw"/><path class="cn_a2nbzv"/><path class="voelu9bol"/><g class="n1mjunbsu"><circle transform="rotate(-45 60.554 87.548)" class="rnnu3tzpv"/><path class="abk3ugb1n"/><path class="vmypq-d8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:wireless" /></template>
<style>
.abk3ugb1n {
  d: path("M60.55 42.83c13.7 0 25.97 6.2 34.17 15.93c.62.74 1.76.73 2.4.01l4.82-5.44c.53-.6.55-1.51.02-2.11c-10.1-11.5-24.9-18.77-41.41-18.77s-31.32 7.27-41.41 18.77c-.53.6-.51 1.51.02 2.11l4.82 5.44c.64.72 1.78.72 2.4-.01c8.21-9.73 20.48-15.93 34.17-15.93");
}

.cn_a2nbzv {
  fill: var(--svg-color--ff9800, #ff9800);
  d: path("M109.7 4H11.5A7.555 7.555 0 0 0 4 11.5v97.9c0 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.5c.09-4.05-3.13-7.41-7.18-7.5z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.rnnu3tzpv {
  cx: 60.55px;
  cy: 87.54px;
  r: 9.97px;
}

.vmypq-d8f {
  d: path("M60.55 66.05c7.97 0 14.95 4.12 18.84 10.28c.57.9 1.82 1.03 2.54.25l5.14-5.62c.51-.55.57-1.4.12-2c-5.95-8.04-15.66-13.28-26.63-13.28s-20.68 5.24-26.63 13.28c-.45.6-.38 1.45.12 2l5.14 5.62c.72.79 1.97.65 2.54-.25c3.89-6.16 10.87-10.28 18.84-10.28Z");
}

.voelu9bol {
  fill: var(--svg-color--ffbd52, #ffbd52);
  d: path("M39.7 12.9c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4c-1.9 2.3-2.3 5.6-2.6 8.4c-.2 2.2-2.2 14.9 3.5 11.2c.68-.45 1.23-1.07 1.6-1.8c1.2-2.1 1.9-3.5 3.3-5.6c5.3-8.6 18.8-10.5 18.8-13.5");
  opacity: var(--svg-opacity--0-75, 0.75);
}

.zoie8jzjw {
  fill: var(--svg-color--f77e00, #f77e00);
  d: path("M116 4H12c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8V12c0-4.42-3.58-8-8-8");
}

</style>
