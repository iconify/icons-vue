<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ioja_rb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vital-signs-rounded" /></template>
<style>
.ioja_rb8p {
  fill: currentColor;
  d: path("M8.948 18.089q-.211-.161-.31-.41L6.57 12.5H2.54q-.213 0-.357-.144t-.143-.357t.143-.356t.357-.143h4.173q.248 0 .447.146t.305.37l1.959 4.93l4.37-10.644q.097-.249.307-.41t.475-.161q.266 0 .477.16q.211.162.31.411L17.47 11.5h4.03q.213 0 .356.144t.144.357t-.144.356t-.356.143h-4.192q-.255 0-.441-.146t-.292-.37l-1.998-4.95l-4.37 10.645q-.097.249-.307.41t-.475.161q-.266 0-.477-.161");
}

</style>
