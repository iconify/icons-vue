<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="anjk6vp9h"/><path class="ywl6mzbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:white-square-button" /></template>
<style>
.anjk6vp9h {
  fill: var(--svg-color--d0d2d3, #d0d2d3);
  d: path("M63.94 57.047a6.89 6.89 0 0 1-6.892 6.898H6.89A6.895 6.895 0 0 1 0 57.047V6.894A6.89 6.89 0 0 1 6.89 0h50.159a6.89 6.89 0 0 1 6.892 6.894v50.153z");
}

.ywl6mzbvx {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M46.49 13.459H17.45a3.99 3.99 0 0 0-3.991 3.991v29.039a3.995 3.995 0 0 0 3.991 3.997h29.04a3.995 3.995 0 0 0 3.993-3.997v-29.04a3.99 3.99 0 0 0-3.993-3.991");
}

</style>
