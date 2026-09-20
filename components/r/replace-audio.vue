<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp3-mns7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:replace-audio" /></template>
<style>
.fp3-mns7k {
  fill: currentColor;
  d: path("M4.327 8.77q.739-2.572 2.864-4.171T12 3q2.223 0 4.099 1.144T19 7.234V4h1v4.77h-4.77v-1h2.862q-.84-1.726-2.49-2.748T12 4Q9.725 4 7.907 5.306t-2.52 3.463zm4.506 11.436q-.794-.794-.794-1.937t.794-1.936t1.936-.794q.497 0 .939.18t.792.49v-5.055h4v1h-3v6.115q0 1.143-.794 1.937T10.769 21t-1.936-.794");
}

</style>
