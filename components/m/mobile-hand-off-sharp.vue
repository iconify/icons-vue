<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4kj37bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-hand-off-sharp" /></template>
<style>
.t4kj37bxp {
  fill: currentColor;
  d: path("m2.33 2.85l19.224 19.223l-.713.708L9.579 11.519l-2.913 3.01L11.785 21H5V6.935L1.623 3.558zM16.078 3v2.135h-2.616v6.046L5.262 3zM9.999 5.999q-.23.23-.23.54q0 .309.23.539t.54.23t.539-.23q.23-.23.23-.54T11.078 6t-.54-.23T10 6m5.847 7.567V7.519h.923l3 3v6.97zM15.777 21q-.43 0-.814-.159q-.384-.158-.66-.508l-4.476-5.64l.73-.731l5.674 2.788l2.952 2.952q-.39.598-1.024.948t-1.39.35z");
}

</style>
