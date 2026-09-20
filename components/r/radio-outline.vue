<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz0a8f1kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:radio-outline" /></template>
<style>
.yz0a8f1kq {
  fill: currentColor;
  d: path("M4.616 21q-.691 0-1.153-.462T3 19.385V8.615q0-.682.434-1.211q.433-.529 1.066-.793l10.4-4.226l.342.88L6.031 7h13.354q.69 0 1.152.463T21 8.616v10.769q0 .69-.463 1.153T19.385 21zm0-1h14.769q.23 0 .423-.192t.192-.424V12.54H4v6.846q0 .23.192.423t.423.192m4.727-2.234q.62-.62.62-1.497t-.62-1.496t-1.496-.62t-1.496.62t-.62 1.496t.62 1.497t1.496.619t1.496-.62M4 11.54h12.5V9.692h1v1.847H20V8.616q0-.231-.192-.424T19.385 8H4.615q-.23 0-.423.192T4 8.616zM4 20v-7.461z");
}

</style>
