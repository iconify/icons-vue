<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh25itb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:switch-access-shortcut-rounded" /></template>
<style>
.fh25itb6d {
  fill: currentColor;
  d: path("M13 5.3q-1.425 1.275-2.212 2.988T10 11.9q0 2.275 1.088 4.263t3.037 3.187q.35.225.488.613t-.063.762t-.575.513t-.725-.063Q10.8 19.7 9.4 17.238T8 11.9q0-2.275.9-4.312T11.45 4H9q-.425 0-.712-.288T8 3t.288-.712T9 2h5q.425 0 .713.288T15 3v5q0 .425-.288.713T14 9t-.712-.288T13 8z");
}

</style>
