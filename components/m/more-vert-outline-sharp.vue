<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsx2arepj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:more-vert-outline-sharp" /></template>
<style>
.bsx2arepj {
  fill: currentColor;
  d: path("M12 18.539q-.413 0-.706-.294T11 17.538t.294-.706t.706-.294t.706.294t.294.706t-.294.707t-.706.293M12 13q-.413 0-.706-.294T11 12t.294-.706T12 11t.706.294T13 12t-.294.706T12 13m0-5.538q-.413 0-.706-.294T11 6.46t.294-.706t.706-.293t.706.293t.294.707t-.294.706T12 7.46");
}

</style>
