<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="i8rntb6dk"/><path class="svcufp50f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:post-parcels-mail" /></template>
<style>
.i8rntb6dk {
  d: path("M12.615 29.172v5.516L25.673 42.5l12.534-7.91V23.395L25.51 31.22l-12.778-7.95l-5.604-9.785L20.678 5.5l4.674 9.76l6.641 4.167");
}

.svcufp50f {
  d: path("m25.51 31.221l2.668-8.948l12.694-8.88l-2.684 10.018m-25.39-.171l12.555-7.97");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
