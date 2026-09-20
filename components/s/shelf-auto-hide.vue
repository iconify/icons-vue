<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycttc31zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shelf-auto-hide" /></template>
<style>
.ycttc31zj {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zM12 17q.31 0 .54-.23t.23-.54t-.23-.539t-.54-.23t-.54.23t-.23.54t.23.54T12 17m-3.46-.23q.23-.23.23-.54q0-.309-.23-.539t-.54-.23t-.54.23t-.23.54t.23.54T8 17t.54-.23M16 17q.31 0 .54-.23t.23-.54t-.23-.539t-.54-.23t-.54.23t-.23.54t.23.54T16 17");
}

</style>
