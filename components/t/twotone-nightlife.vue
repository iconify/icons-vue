<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8voavijn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-nightlife" /></template>
<style>
.z8voavijn {
  fill: currentColor;
  d: path("M1 5h14l-6 9v4h2v2H5v-2h2v-4zm9.1 4l1.4-2H4.49l1.4 2zM17 5h5v3h-3v9c0 1.66-1.34 3-3 3s-3-1.34-3-3s1.34-3 3-3a3 3 0 0 1 1 .17z");
}

</style>
