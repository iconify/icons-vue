<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aug94zfxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-camera-rear" /></template>
<style>
.aug94zfxu {
  fill: currentColor;
  d: path("m10.35 21.808l-.708-.708l1.6-1.6H6v-1h5.242l-1.6-1.6l.708-.708L13.158 19zM14 19.5v-1h4v1zM12.588 7.087q.22-.22.22-.549t-.22-.549t-.55-.22t-.548.22t-.22.55t.22.548t.549.22t.549-.22M6 17V4.616q0-.691.463-1.153T7.616 3h8.769q.69 0 1.153.463T18 4.616V7.83q.373.04.648.31q.275.269.275.648v1.769q0 .379-.275.648t-.648.31V17h-5.417l-2.233-2.233L8.112 17z");
}

</style>
