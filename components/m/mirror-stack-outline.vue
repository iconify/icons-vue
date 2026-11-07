<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kto7wbbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mirror-stack-outline" /></template>
<style>
.kto7wbbik {
  fill: currentColor;
  d: path("M13.423 17.23v-1h3.962q.23 0 .423-.191t.192-.424v-11q0-.23-.192-.423T17.384 4h-5.192q-.23 0-.423.192t-.192.423v2.423h-1V4.616q0-.69.463-1.153T12.192 3h5.193q.69 0 1.153.463T19 4.615v11q0 .69-.462 1.153t-1.153.463zM6.616 20h5.192q.23 0 .423-.192t.192-.424V8.404q0-.231-.192-.423t-.423-.192H6.616q-.231 0-.424.192T6 8.404v10.98q0 .232.192.424t.423.192m0 1q-.69 0-1.153-.462T5 19.385V8.404q0-.69.463-1.153t1.153-.462h5.192q.67 0 1.143.472q.472.472.472 1.143v10.98q0 .691-.462 1.154T11.808 21zM6 20V7.789zM18 4.596V4v12.23z");
}

</style>
