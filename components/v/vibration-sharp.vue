<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjx47jxxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:vibration-sharp" /></template>
<style>
.wjx47jxxp {
  fill: currentColor;
  d: path("M0 15V9h2v6zm3 2V7h2v10zm19-2V9h2v6zm-3 2V7h2v10zM6 21V3h12v18zm6.713-13.288Q13 7.425 13 7t-.288-.712T12 6t-.712.288T11 7t.288.713T12 8t.713-.288");
}

</style>
