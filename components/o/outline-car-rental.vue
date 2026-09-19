<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="g5g143_gf"/><circle class="jq19wbb4z"/><path class="o-rm2dy7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-car-rental" /></template>
<style>
.g5g143_gf {
  cx: 9px;
  cy: 16.5px;
  r: 1px;
  fill: currentColor;
}

.jq19wbb4z {
  cx: 15px;
  cy: 16.5px;
  r: 1px;
  fill: currentColor;
}

.o-rm2dy7z {
  fill: currentColor;
  d: path("M17.25 9.6c-.02-.02-.03-.04-.05-.07c-.38-.52-.92-.53-.92-.53H7.72s-.54.01-.92.54c-.02.02-.03.04-.05.06c-.07.11-.14.24-.19.4c-.22.66-.74 2.22-1.56 4.69v6.5c0 .45.35.81.78.81h.44c.43 0 .78-.36.78-.81V20h10v1.19c0 .45.34.81.78.81h.44c.43 0 .78-.36.78-.81v-6.5c-.82-2.46-1.34-4.03-1.56-4.69c-.05-.16-.12-.29-.19-.4M8.33 11h7.34l.23.69l.43 1.31H7.67zM17 18H7v-3h10zM10.83 3A3.01 3.01 0 0 0 8 1C6.34 1 5 2.34 5 4c0 1.65 1.34 3 3 3c1.3 0 2.41-.84 2.83-2H16v2h2V5h1V3zM8 5c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1");
}

</style>
