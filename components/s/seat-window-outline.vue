<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0kmazh6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:seat-window-outline" /></template>
<style>
.w0kmazh6h {
  fill: currentColor;
  d: path("M14.175 9q-.273 0-.475-.161t-.283-.43l-1.27-4.384q-.106-.385.133-.705q.24-.32.643-.32h5.94q.274 0 .476.162t.282.429l1.271 4.384q.106.385-.133.705q-.24.32-.643.32zm.154-1h5.519l-1.144-4H13.17zm-8.483-.423q-.69 0-1.191-.501t-.501-1.191t.5-1.192t1.192-.5t1.192.5t.5 1.191q0 .691-.5 1.192t-1.192.501M11.962 20h-5.95q-.69 0-1.244-.443q-.552-.443-.69-1.134L2 8h1.012l2.084 10.385q.038.23.27.423q.23.192.461.192h6.134zm5.077 2.385L14.484 18H7.267q-.552 0-.946-.332t-.505-.845l-1.177-5.62q-.211-1.026.47-1.75q.68-.722 1.592-.722q.702 0 1.29.419t.749 1.146L9.954 16h3.711q.39 0 .726.198q.334.198.551.571l2.962 5.116zM14.329 8L13.17 4z");
}

</style>
