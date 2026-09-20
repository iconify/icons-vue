<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elps2o55b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:seat-window-outline-rounded" /></template>
<style>
.elps2o55b {
  fill: currentColor;
  d: path("M14.175 9q-.273 0-.475-.161t-.283-.43l-1.27-4.384q-.106-.385.133-.705q.24-.32.643-.32h5.94q.274 0 .476.162t.282.429l1.271 4.384q.106.385-.133.705q-.24.32-.643.32zm.154-1h5.519l-1.144-4H13.17zm-8.483-.423q-.69 0-1.191-.501t-.501-1.191t.5-1.192t1.192-.5t1.192.5t.5 1.191q0 .691-.5 1.192t-1.192.501M6.012 20q-.69 0-1.244-.443q-.552-.443-.69-1.134L2.11 8.585q-.061-.226.095-.405T2.61 8q.177 0 .307.11q.131.11.168.286l2.011 9.989q.039.23.27.423q.23.192.461.192h5.635q.213 0 .356.143t.144.357t-.144.357t-.356.143zm8.473-2h-7.22q-.551 0-.945-.332t-.505-.845l-1.177-5.62q-.211-1.026.47-1.75q.68-.722 1.592-.722q.702 0 1.29.419t.749 1.146L9.954 16h3.711q.39 0 .726.198q.334.198.551.571l2.712 4.683q.104.177.049.378q-.055.2-.232.304t-.378.05q-.2-.055-.305-.232zm-.156-10L13.17 4z");
}

</style>
