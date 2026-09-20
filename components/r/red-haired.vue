<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="o0qzs8b8b"/><path class="bfs5h2b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:red-haired" /></template>
<style>
.bfs5h2b9f {
  fill: var(--svg-color--e95f28, #E95F28);
  d: path("M4.5 1c-1.567 0-3.061.086-4.5.235v23.416c13.81 13.743 6.846-.189 6.846-.189c4.692 4.692 18.769 4.692 18.769 4.692L29.038 36h5.28c.424-2.252.682-5.332.682-9.192C35 15.077 23.269 1 4.5 1z");
}

.o0qzs8b8b {
  fill: var(--svg-color--ffdc5d, #FFDC5D);
  d: path("M0 21h30v15H0z");
}

</style>
