<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="jpb2feb0e"/><path class="qj3xvgbyr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:new-world" /></template>
<style>
.jpb2feb0e {
  d: path("M24.109 38.66L3.5 24.078L23.891 9.34L44.5 23.922zM12.601 17.499l22.82.01M12.568 30.362l23.024-.002M23.881 9.584l-.07 7.92m.296 20.716l-.028-7.859");
}

.qj3xvgbyr {
  d: path("m27.58 17.504l-3.698-7.92l-3.86 7.92m9.158 13.124l-5.073 7.87l-4.616-8.147m-3.93-2.269v-8.295l5.495 8.295v-8.295m11.607 0l-2.074 8.295l-2.074-8.295l-2.073 8.295l-2.074-8.295");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
