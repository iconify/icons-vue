<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k9zukdb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:spotiflac" /></template>
<style>
.k9zukdb6a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.845 13.754v4.252m4.105-8.513v12.162m3.894-16.038v29.076m-5.128-4.784l5.128 4.784l5.127-4.784m-.938-20.416v12.162m4.127-7.972v4.252m1.22 17.195v3.658c0 2.261-1.43 3.596-3.409 3.596H18.466c-2.908 0-3.845-1.125-3.845-3.596V35.13");
}

</style>
