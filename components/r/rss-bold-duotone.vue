<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="bjctctb5d"/><path class="k9hzafcmp"/></g><path class="eaczmyb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rss-bold-duotone" /></template>
<style>
.bjctctb5d {
  d: path("M4 11.25C8.83251 11.25 12.75 15.1675 12.75 20C12.75 20.4142 12.4142 20.75 12 20.75C11.5858 20.75 11.25 20.4142 11.25 20C11.25 15.9959 8.00409 12.75 4 12.75C3.58579 12.75 3.25 12.4142 3.25 12C3.25 11.5858 3.58579 11.25 4 11.25Z");
}

.eaczmyb0t {
  fill: currentColor;
  d: path("M4 19.25C4.41421 19.25 4.75 19.5858 4.75 20C4.75 20.4142 4.41421 20.75 4 20.75C3.58579 20.75 3.25 20.4142 3.25 20C3.25 19.5858 3.58579 19.25 4 19.25Z");
}

.k9hzafcmp {
  d: path("M4 3.25C13.2508 3.25 20.75 10.7492 20.75 20C20.75 20.4142 20.4142 20.75 20 20.75C19.5858 20.75 19.25 20.4142 19.25 20C19.25 11.5776 12.4224 4.75 4 4.75C3.58579 4.75 3.25 4.41421 3.25 4C3.25 3.58579 3.58579 3.25 4 3.25Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
