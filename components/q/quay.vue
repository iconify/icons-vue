<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":236};
const content = `<path class="kmnxp84vb"/><path class="bpj2-ro8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:quay" /></template>
<style>
.bpj2-ro8m {
  fill: var(--svg-color--003764, #003764);
  d: path("M152.842 235.032L97.287 117.514L152.842 0h47.295l-55.555 117.514l55.555 117.518zm-97.287 0L0 117.514L55.555 0h47.296L47.295 117.514l55.556 117.518z");
}

.kmnxp84vb {
  fill: var(--svg-color--40b4e5, #40b4e5);
  d: path("m200.134 0l55.555 117.514l-55.555 117.518h-47.295l55.555-117.518L152.84 0zM110.08 99.836l20.056-38.092l-2.29-8.868L102.847 0H55.552l48.647 102.898zm17.766 74.433l-17.333-39.034l-6.314-3.101l-48.647 102.898h47.295l25-52.88z");
}

</style>
