<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh0n7abid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-camera-outline-sharp" /></template>
<style>
.kh0n7abid {
  fill: currentColor;
  d: path("m17.525 15l-2.175-1.25l3.5-2.6L21 12.4zM12.8 11.95l2.6-1.975L8.5 6L7 8.6zM4 20v-2h5v-5.95L4.275 9.325l3.5-6.05l11.25 6.5l-6.1 4.55l-1.925-1.1V20zm7.2-11.025");
}

</style>
