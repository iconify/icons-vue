<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atb9-obta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:web-outline-rounded" /></template>
<style>
.atb9-obta {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm0-1H15v-3.884H4v3.269q0 .23.192.423t.423.192M16 18h3.385q.23 0 .423-.192t.192-.424V9.231h-4zM4 13.116h11V9.23H4z");
}

</style>
