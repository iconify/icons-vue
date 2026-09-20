<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u14p06b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switch" /></template>
<style>
.u14p06b8l {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3h10.788q.69 0 1.153.463t.462 1.153v14.769q0 .69-.462 1.153T17.404 21zm2.096-4.711h6.577V7.73H8.71zm1-1v-4.673h4.577v4.673zm2.285-9.25q.29 0 .483-.19t.193-.48t-.19-.484t-.48-.193t-.483.19t-.193.48t.19.483t.48.193m0 13.289q.29 0 .483-.19t.193-.48t-.19-.483t-.48-.193t-.483.19t-.193.48t.19.483t.48.193");
}

</style>
