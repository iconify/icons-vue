<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urqwpub5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:toolbar-outline" /></template>
<style>
.urqwpub5z {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zM5 8h14V5.616q0-.231-.192-.424T18.384 5H5.616q-.231 0-.424.192T5 5.616zm14 1H5v9.385q0 .23.192.423t.423.192h12.77q.23 0 .423-.192t.192-.423zM5 8v1zm0 0V5zm0 1v10z");
}

</style>
