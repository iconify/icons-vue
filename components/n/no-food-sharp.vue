<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt5iu_y1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:no-food-sharp" /></template>
<style>
.dt5iu_y1x {
  fill: currentColor;
  d: path("m20.09 22.53l-7.146-7.145H2.442q0-1.737 1.79-2.984t4.826-1.247q.298 0 .592.012t.554.051v1.421L.867 3.308l.714-.714l19.223 19.223zM2.443 18.693v-1h13.231v1zm0 3.308v-1h13.231v1zm17.875-3.48l-8.482-8.497l-.508-3.638h4.615v-4h1v4h4.616z");
}

</style>
