<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2j4hnbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sports-cricket-outline-rounded" /></template>
<style>
.i2j4hnbud {
  fill: currentColor;
  d: path("m14.308 14.046l-2.262 2.262q-.242.242-.546.242t-.546-.242L2.992 8.346q-.242-.242-.261-.521t.223-.521l2.338-2.338q.243-.243.514-.243t.513.243l8.008 8.007q.242.243.233.537q-.01.294-.252.536M11.5 15.44l1.938-1.939L5.8 5.862L3.862 7.8zm6.746 5.515l-3.973-3.973l.708-.708l3.973 3.973q.14.14.15.345q.01.203-.15.363t-.354.16t-.354-.16M16.544 7.456q-.813-.814-.813-1.956t.813-1.956t1.956-.813t1.956.813t.813 1.956t-.813 1.956t-1.956.813t-1.956-.813m3.21-.701q.515-.515.515-1.255t-.514-1.255t-1.255-.514t-1.255.514t-.514 1.255t.514 1.255t1.255.514t1.255-.514M8.65 10.65");
}

</style>
