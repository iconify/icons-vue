<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="je1dbqbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-3-sharp" /></template>
<style>
.je1dbqbpz {
  fill: currentColor;
  d: path("M12.729 15.492q.619-.298.823-.936t-.18-1.19q-1.316-1.897-2.602-3.762T8.16 5.86q.601 2.225 1.212 4.406q.61 2.182 1.278 4.376q.192.652.822.898q.63.245 1.257-.048M4.458 19q-.702-1.287-1.086-2.454q-.383-1.167-.378-2.657q0-1.847.732-3.47t1.965-2.83t2.87-1.898T12 5q1.864 0 3.503.71q1.64.711 2.858 1.93t1.929 2.857Q21 12.137 21 14q0 1.466-.397 2.599T19.503 19z");
}

</style>
