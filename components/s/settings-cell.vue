<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a76j26i2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-cell" /></template>
<style>
.a76j26i2q {
  fill: currentColor;
  d: path("M8 21.789q-.31 0-.54-.23t-.23-.54t.23-.54t.54-.229t.54.23t.23.54t-.23.539t-.54.23m3.46-.23q-.23-.23-.23-.54t.23-.54q.23-.229.54-.229t.54.23t.23.54t-.23.539t-.54.23t-.54-.23m4 0q-.23-.23-.23-.54t.23-.54q.23-.229.54-.229t.54.23t.23.54t-.23.539t-.54.23t-.54-.23M12.587 6.086q.22-.222.22-.549t-.22-.547q-.223-.22-.55-.22t-.548.22q-.22.222-.22.55t.222.547t.549.22t.548-.22m4.604-2.472v2.127q.31-.002.52.241t.211.55v1.28q0 .306-.21.55q-.211.243-.52.24v7.782q0 .666-.475 1.14T15.577 18H8.423q-.666 0-1.14-.475t-.475-1.14V3.615q0-.666.474-1.14T8.423 2h7.154q.666 0 1.14.475t.475 1.14");
}

</style>
