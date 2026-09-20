<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4hflrnxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:notifications-paused-sharp" /></template>
<style>
.l4hflrnxk {
  fill: currentColor;
  d: path("M4 19v-2h2v-7q0-2.075 1.25-3.687T10.5 4.2V2h3v2.2q2 .5 3.25 2.113T18 10v7h2v2zm8 3q-.825 0-1.412-.587T10 20h4q0 .825-.587 1.413T12 22m-2.75-6h5.5v-1.8H12l2.75-3.4V9h-5.5v1.8H12l-2.75 3.4z");
}

</style>
