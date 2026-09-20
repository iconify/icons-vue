<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="c8e1z_bsf"/><path class="dj42u5atl"/><path class="ms3kx9nmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mytel-myid" /></template>
<style>
.c8e1z_bsf {
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4m19.822 13.565v8.71");
}

.dj42u5atl {
  d: path("M9.551 27.666v-8.602l4.338 8.71l4.337-8.71v8.71m7.717-2.05v2.94a2.18 2.18 0 0 1-2.169 2.177c-.65 0-1.193-.218-1.518-.653");
}

.ms3kx9nmu {
  d: path("M25.943 22.004v3.593a2.18 2.18 0 0 1-2.169 2.178a2.18 2.18 0 0 1-2.169-2.178v-3.593m11.097 5.771v-8.71h1.952c2.06 0 3.795 1.742 3.795 3.81v1.09c0 2.068-1.735 3.81-3.795 3.81z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
