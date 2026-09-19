<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huqsl3b9n"/><path class="c5ffibcpj"/><path class="z6k6deb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-deck" /></template>
<style>
.c5ffibcpj {
  fill: currentColor;
  d: path("M22 9L12 2L2 9h9v13h2V9zM12 4.44L15.66 7H8.34z");
}

.huqsl3b9n {
  fill: currentColor;
  d: path("M12 4.44L8.34 7h7.32z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.z6k6deb5g {
  fill: currentColor;
  d: path("m4.14 12l-1.96.37l.82 4.37V22h2l.02-4H7v4h2v-6H4.9zm14.96 4H15v6h2v-4h1.98l.02 4h2v-5.26l.82-4.37l-1.96-.37z");
}

</style>
