<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg0c50bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:two-pager-store-outline-sharp" /></template>
<style>
.wg0c50bhq {
  fill: currentColor;
  d: path("M3 19V5h18v6.116h-1V6h-7.5v5.116h-1V6H4v12h7.5v1zm11 2v-3.75h1V20h5v-2.75h1V21zm-1.104-3.5l.788-4h7.632l.788 4zm1.213-1h6.782l-.393-2h-5.996zm-8.724-1h4.73v-1h-4.73zm0-3h4.73v-1h-4.73zm0-3h4.73v-1h-4.73zm8.5 0v-1h4.73v1zM4 18V6z");
}

</style>
