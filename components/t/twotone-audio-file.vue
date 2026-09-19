<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssmab7vza"/><path class="eh3kqxbey"/><path class="t9pjjnyly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-audio-file" /></template>
<style>
.eh3kqxbey {
  fill: currentColor;
  d: path("M14 2H6c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V8zm4 18H6V4h7v5h5z");
}

.ssmab7vza {
  fill: currentColor;
  d: path("M13 4H6v16h12V9h-5zm3 7v2h-3v3.75c0 1.24-1.01 2.25-2.25 2.25S8.5 17.99 8.5 16.75s1.01-2.25 2.25-2.25c.46 0 .89.14 1.25.38V11z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.t9pjjnyly {
  fill: currentColor;
  d: path("M12 14.88a2.247 2.247 0 0 0-3.5 1.87c0 1.24 1.01 2.25 2.25 2.25S13 17.99 13 16.75V13h3v-2h-4z");
}

</style>
