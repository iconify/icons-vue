<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apuua4x1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:phone-missed-outline-sharp" /></template>
<style>
.apuua4x1m {
  fill: currentColor;
  d: path("m4.064 19.866l-2.972-2.91l.635-.66q2.106-2.179 4.841-3.237T12 12t5.407 1.071t4.847 3.225l.654.66l-2.971 2.91l-3.437-2.597v-3.465q-1.142-.396-2.277-.6T12 13t-2.223.204t-2.277.6v3.465zM6.5 14.18q-1.129.529-2.17 1.237T2.509 16.9l1.654 1.654L6.5 16.769zm11 .011v2.539l2.339 1.823l1.692-1.604q-.917-.842-1.9-1.529T17.5 14.192m-5.492-3.496L7.019 5.708V9h-1V4h5v1H7.727l4.275 4.275l5.323-5.323l.714.714z");
}

</style>
