<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jabesrbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:measuring-tape-rounded" /></template>
<style>
.jabesrbst {
  fill: currentColor;
  d: path("M13.116 19H7.23q-.666 0-1.141-.475t-.475-1.14V11.5q0-3.132 2.183-5.316T13.112 4t5.317 2.183t2.187 5.313t-2.184 5.318T13.116 19m2.128-5.371q.872-.871.872-2.129t-.872-2.129t-2.128-.871t-2.13.871t-.87 2.129t.87 2.129t2.13.871t2.128-.871m-3.547-.713q-.581-.584-.581-1.418t.584-1.416t1.418-.582t1.416.584t.582 1.418t-.584 1.416t-1.419.582t-1.416-.584M3.884 19q-.213 0-.356-.144t-.143-.356v-3q0-.213.144-.356T3.885 15t.356.144t.144.356v3q0 .213-.144.356q-.144.144-.357.144");
}

</style>
