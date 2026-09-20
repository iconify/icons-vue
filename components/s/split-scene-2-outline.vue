<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nop0-f7ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:split-scene-2-outline" /></template>
<style>
.nop0-f7ne {
  fill: currentColor;
  d: path("M6.616 20q-.691 0-1.153-.462T5 18.384v-3.5h1v3.5q0 .231.192.424t.423.192h10.77q.23 0 .423-.192t.192-.424v-3.5h1v3.5q0 .691-.462 1.153T17.384 20zM3 12.5v-1h2V5.616q0-.691.463-1.153T6.616 4h10.769q.69 0 1.153.463T19 5.616V11.5h2v1zm3-1h12V5.616q0-.231-.192-.424T17.384 5H6.616q-.231 0-.424.192T6 5.616zM18 19H6zm0-14H6z");
}

</style>
