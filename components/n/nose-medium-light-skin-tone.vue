<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="jzqidd-gg"/><path class="zu_a7nrol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:nose-medium-light-skin-tone" /></template>
<style>
.jzqidd-gg {
  fill: var(--svg-color--e0bb95, #e0bb95);
  d: path("M90.32 62.5c-5.16-32.75-6.83-53-6.83-53H44.72s-1.66 20.25-6.83 53c-2.7 17.1-13.73 11.12-14 38.9c-.16 16.52 18.76 11.75 25.88 12.82c9.27 1.4 5.79 4.18 14.12 4.27h.44c8.33-.09 4.85-2.87 14.12-4.27c7.12-1.08 26.04 3.7 25.88-12.82c-.28-27.78-11.31-21.8-14.01-38.9");
}

.zu_a7nrol {
  fill: var(--svg-color--c48e6a, #c48e6a);
  d: path("M35.18 103.18s9.89-12.13 18.76-.94c7.8 9.84-3.19 6.56-8.51 5.62c-9.29-1.63-13.2 3.82-10.25-4.68m57.86 0s-9.89-12.13-18.76-.94c-7.8 9.84 3.19 6.56 8.51 5.62c9.29-1.63 13.2 3.82 10.25-4.68");
}

</style>
