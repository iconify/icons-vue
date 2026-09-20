<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmt6ivb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-landscape-outline-sharp" /></template>
<style>
.cmt6ivb0l {
  fill: currentColor;
  d: path("M1 19V5h5.1V4h4.8v1H23v14zm20-2V7H3v10zM3 17V7zm2.713-4.288Q6 12.425 6 12t-.288-.712T5 11t-.712.288T4 12t.288.713T5 13t.713-.288");
}

</style>
