<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko424dbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:videocam-alert-outline-sharp" /></template>
<style>
.ko424dbmv {
  fill: currentColor;
  d: path("M17.48 19h-5.728q.133-.238.245-.479q.113-.24.192-.521h4.292V6h-12v3.833q-.281.073-.521.176t-.48.216V5h14v6.27l3.04-3.04v7.54l-3.04-3.04zm-14.315-.164Q2 17.67 2 16t1.165-2.835T6 12t2.836 1.165T10 16t-1.164 2.836T6 20t-2.835-1.164M6 18.423q.2 0 .33-.13t.132-.332t-.131-.33T6 17.5t-.33.13t-.132.332t.131.33t.331.131m-.385-1.846h.77v-3h-.77z");
}

</style>
