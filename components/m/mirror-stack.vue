<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgcb66brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mirror-stack" /></template>
<style>
.rgcb66brs {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385V8.404q0-.69.463-1.153t1.153-.462h5.192q.67 0 1.143.472q.472.472.472 1.143v10.98q0 .691-.462 1.154T11.808 21zm9-3.77V7.02q0-1.02-.702-1.722t-1.722-.702h-2.615q0-.671.463-1.133T12.192 3h5.193q.69 0 1.152.463T19 4.616v11q0 .69-.463 1.152t-1.153.463z");
}

</style>
