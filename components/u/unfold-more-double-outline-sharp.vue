<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgd8u3bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:unfold-more-double-outline-sharp" /></template>
<style>
.sgd8u3bil {
  fill: currentColor;
  d: path("M12.025 23.975L7.45 19.4l1.4-1.4l3.175 3.15l3.175-3.175l1.4 1.425zm0-5L7.45 14.4l1.4-1.4l3.175 3.15l3.175-3.175l1.4 1.425zM8.85 11L7.425 9.575l4.6-4.6l4.575 4.6L15.175 11l-3.15-3.175zm0-5L7.425 4.575l4.6-4.6l4.575 4.6L15.175 6l-3.15-3.175z");
}

</style>
