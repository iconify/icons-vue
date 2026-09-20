<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwiyv5veg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:problem" /></template>
<style>
.xwiyv5veg {
  fill: currentColor;
  d: path("M7.549 15.934q.22-.22.22-.55q0-.328-.22-.548T7 14.616t-.549.22t-.22.549t.22.549t.549.22t.549-.22M6.5 13.23h1V7.846h-1zm4 1.269h7v-1h-7zm0-4h7v-1h-7zM4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19z");
}

</style>
