<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4fd--bea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:video-frame-save" /></template>
<style>
.v4fd--bea {
  fill: currentColor;
  d: path("M20 10V6.616q0-.231-.192-.424T19.385 6H16V5h3.385q.69 0 1.152.463T21 6.616V10zM3 10V6.616q0-.691.463-1.153T4.615 5H8v1H4.616q-.231 0-.424.192T4 6.616V10zm1.616 9q-.691 0-1.153-.462T3 17.384V14h1v3.385q0 .23.192.423t.423.192H8v1zM10 15.577V8.423L15.577 12zm5.77 7.917v-1h7v1zm3.5-2.725l-3.308-3.307l.707-.708l2.1 2.088v-4.88h1v4.88l2.1-2.088l.708.707z");
}

</style>
