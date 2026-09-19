<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5m2ru1md"/><path class="atla1bcob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-holiday-village" /></template>
<style>
.atla1bcob {
  fill: currentColor;
  d: path("m8 4l-6 6v10h12V10zm4 14H9v-3H7v3H4v-7.17l4-4l4 4zm-3-5H7v-2h2zm9 7V8.35L13.65 4h-2.83L16 9.18V20zm4 0V6.69L19.31 4h-2.83L20 7.52V20z");
}

.n5m2ru1md {
  fill: currentColor;
  d: path("m8 6.83l-4 4V18h3v-3h2v3h3v-7.17zM9 13H7v-2h2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
