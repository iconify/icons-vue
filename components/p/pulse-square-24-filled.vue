<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlfhi6brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pulse-square-24-filled" /></template>
<style>
.mlfhi6brm {
  fill: currentColor;
  d: path("M17.75 3A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3zm-6.604 4.868a.75.75 0 0 0-1.334.08L8.256 11.5H6.75l-.103.007A.75.75 0 0 0 6.75 13h1.995l.11-.008a.75.75 0 0 0 .577-.44l1.035-2.363l2.337 5.835l.047.1a.75.75 0 0 0 1.319-.043L15.714 13h1.537l.101-.007a.75.75 0 0 0-.101-1.493h-2l-.105.008a.75.75 0 0 0-.566.406l-1.003 2.004l-2.382-5.946z");
}

</style>
