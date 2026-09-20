<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1y1swbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pause-circle-rounded" /></template>
<style>
.t1y1swbkn {
  fill: currentColor;
  d: path("M10.665 15.356q.143-.143.143-.356V9q0-.213-.144-.356t-.357-.144t-.356.144T9.808 9v6q0 .213.144.356q.144.144.356.144q.213 0 .357-.144m3.384 0q.143-.144.143-.356V9q0-.213-.144-.356q-.144-.144-.356-.144q-.213 0-.357.144T13.192 9v6q0 .213.144.356t.357.144t.356-.144M12.003 21q-1.866 0-3.51-.708q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709");
}

</style>
