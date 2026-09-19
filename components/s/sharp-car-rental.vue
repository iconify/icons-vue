<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojoytpwqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-car-rental" /></template>
<style>
.ojoytpwqc {
  fill: currentColor;
  d: path("M10.83 3A3.01 3.01 0 0 0 8 1C6.34 1 5 2.34 5 4c0 1.65 1.34 3 3 3c1.3 0 2.41-.84 2.83-2H16v2h2V5h1V3zM8 5c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m9.11 4H6.89L5 14.69V22h2v-2h10v2h2v-7.31zM9 17.5c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m6 0c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1M7.67 13l.66-2h7.34l.66 2z");
}

</style>
