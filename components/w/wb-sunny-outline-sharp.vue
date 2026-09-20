<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by8z61bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wb-sunny-outline-sharp" /></template>
<style>
.by8z61bpb {
  fill: currentColor;
  d: path("M11 4V1h2v3zm0 19v-3h2v3zm9-10v-2h3v2zM1 13v-2h3v2zm17.7-6.3l-1.4-1.4l1.75-1.8l1.45 1.45zM4.95 20.5L3.5 19.05l1.8-1.75l1.4 1.4zm14.1 0l-1.75-1.8l1.4-1.4l1.8 1.75zM5.3 6.7L3.5 4.95L4.95 3.5L6.7 5.3zm2.45 9.55Q6 14.5 6 12t1.75-4.25T12 6t4.25 1.75T18 12t-1.75 4.25T12 18t-4.25-1.75m7.088-1.412Q16 13.675 16 12t-1.162-2.838T12 8T9.162 9.163T8 12t1.163 2.838T12 16t2.838-1.162M12 12");
}

</style>
