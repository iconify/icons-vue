<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aid3v3bqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-ad-off" /></template>
<style>
.aid3v3bqm {
  fill: currentColor;
  d: path("M5.73 15.885h8.728l-1-1H5.73zm0-3.385h5.343l-1-1H5.731zm0-3.384h1.96l-1-1h-.96zM21.105 22.53L17.573 19H4.616q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5H5l1 1H4.573L1.881 3.308l.713-.714l19.223 19.223zm-.252-4.49l-5.54-5.541h2.957v-1h-3.957l-2.385-2.384H14.5v-1h-3.573L7.812 5h11.573q.69 0 1.152.463T21 6.616v10.769q0 .173-.04.343t-.108.313");
}

</style>
