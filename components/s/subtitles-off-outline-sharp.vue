<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml6107bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:subtitles-off-outline-sharp" /></template>
<style>
.ml6107bym {
  fill: currentColor;
  d: path("M3 19V5h1.808l1 1H4v12h12.38l-2.576-2.577H6.577v-1h6.227L2.38 3.989l.708-.708l16.977 16.977l-.708.708L17.38 19zm17-1.658V6H8.658l-1-1H21v13.342zm-5.496-5.496l-1-1h3.919v1zm-7.927 0v-1h1v1zm3.902.252");
}

</style>
