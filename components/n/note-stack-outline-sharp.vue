<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="puulzw_na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:note-stack-outline-sharp" /></template>
<style>
.puulzw_na {
  fill: currentColor;
  d: path("M8 21V7.994h13v8.583L16.577 21zm1-1h7v-4h4V9H9zm-3.988-2.194L2.752 5.01l12.794-2.259l.504 2.864h-1.012l-.31-1.712L3.905 5.829l1.712 9.63V17.7zM14.5 14.5");
}

</style>
