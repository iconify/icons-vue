<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il341xbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:queue-play-next-outline" /></template>
<style>
.il341xbsm {
  fill: currentColor;
  d: path("m19.5 21.73l-.73-.73l3-3l-3-3l.73-.73L23.23 18zM9 20v-2H4.616q-.691 0-1.153-.462T3 16.384V5.616q0-.691.463-1.153T4.615 4h14.77q.69 0 1.152.463T21 5.616V12h-1V5.616q0-.231-.192-.424T19.385 5H4.615q-.23 0-.423.192T4 5.616v10.769q0 .23.192.423t.423.192H17v1h-2.23v2zm2.5-5.5h1v-3h3v-1h-3v-3h-1v3h-3v1h3zM4 17V5z");
}

</style>
