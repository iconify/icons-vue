<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hl3op4bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:measuring-tape-sharp" /></template>
<style>
.hl3op4bqs {
  fill: currentColor;
  d: path("M5.616 19v-7.5q0-3.132 2.182-5.316T13.112 4t5.317 2.183t2.187 5.313t-2.184 5.318T13.116 19zm9.628-5.371q.872-.871.872-2.129t-.872-2.129t-2.128-.871t-2.13.871t-.87 2.129t.87 2.129t2.13.871t2.128-.871m-3.547-.713q-.581-.584-.581-1.418t.584-1.416t1.418-.582t1.416.584t.582 1.418t-.584 1.416t-1.419.582t-1.416-.584M3.385 19v-4h1v4z");
}

</style>
