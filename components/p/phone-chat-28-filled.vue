<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="bls2o8exm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-chat-28-filled" /></template>
<style>
.bls2o8exm {
  fill: currentColor;
  d: path("M9.75 2A2.75 2.75 0 0 0 7 4.75v18.5A2.75 2.75 0 0 0 9.75 26h3.33l.66-2.251A7.5 7.5 0 0 1 21 13.017V4.75A2.75 2.75 0 0 0 18.25 2zm17.255 18.5a6.5 6.5 0 0 1-9.648 5.688l-2.717.791a.5.5 0 0 1-.62-.62l.795-2.713a6.5 6.5 0 1 1 12.19-3.146m-9-1.5a.5.5 0 1 0 0 1h5a.5.5 0 0 0 0-1zm-.5 2.5a.5.5 0 0 0 .5.5h2.5a.5.5 0 0 0 0-1h-2.5a.5.5 0 0 0-.5.5");
}

</style>
