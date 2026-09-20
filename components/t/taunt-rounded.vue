<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw_82sgzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:taunt-rounded" /></template>
<style>
.vw_82sgzb {
  fill: currentColor;
  d: path("M5.412 14.514q-.427.228-.91.099q-.483-.13-.736-.532q-.31-.514-.103-1.077t.778-.762l8.028-2.775q.177-.067.36.018q.185.086.313.319q.104.196.034.4t-.247.31zm2.03 5.755q-.67 0-1.143-.472q-.472-.472-.472-1.143v-3.271l8.048-4.227q.35-.2.475-.578t-.05-.728l4.325-2.17q.202-.103.407-.017t.358.354q.098.172.05.358t-.21.31l-6.403 4.834v5.135q0 .671-.472 1.143t-1.143.472zM5.564 10.13Q4.692 9.258 4.692 8t.872-2.129T7.692 5t2.13.871t.87 2.129t-.87 2.129t-2.13.871t-2.128-.871");
}

</style>
