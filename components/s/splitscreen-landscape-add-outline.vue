<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hann7jbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:splitscreen-landscape-add-outline" /></template>
<style>
.hann7jbhp {
  fill: currentColor;
  d: path("M13.192 15.616h4.424V8.385h-4.424zm-6.807 0h4.423V8.385H6.385zM19.769 8V6h-2V5h2V3h1v2h2v1h-2v2zM4 18V6zm17-7.616v7q0 .691-.462 1.153T19.385 19H4.615q-.69 0-1.152-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h10.77v1H4.615q-.23 0-.423.192T4 6.616v10.769q0 .23.192.423t.423.192h14.77q.23 0 .423-.192t.192-.423v-7z");
}

</style>
