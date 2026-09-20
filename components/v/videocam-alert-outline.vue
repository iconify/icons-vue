<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehg_hbc4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:videocam-alert-outline" /></template>
<style>
.ehg_hbc4j {
  fill: currentColor;
  d: path("M15.866 19h-4.114q.133-.238.245-.479q.113-.24.192-.521h3.677q.269 0 .442-.173t.173-.442V6.615q0-.269-.173-.442T15.866 6H5.096q-.269 0-.442.173t-.173.443v3.217q-.281.073-.522.176q-.24.103-.478.216v-3.61q0-.69.462-1.152T5.096 5h10.77q.69 0 1.152.463t.463 1.153v4.653l3.038-3.038v7.538l-3.038-3.038v4.654q0 .69-.463 1.153T15.866 19m-12.701-.164Q2 17.67 2 16t1.165-2.835T6 12t2.836 1.165T10 16t-1.164 2.836T6 20t-2.835-1.164M6 18.423q.2 0 .33-.13t.132-.332t-.131-.33T6 17.5t-.33.13t-.132.332t.131.33t.331.131m-.385-1.846h.77v-3h-.77z");
}

</style>
