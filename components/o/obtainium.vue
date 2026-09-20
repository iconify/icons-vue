<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5gyd0c0a.css';
import '../../css/d/dlbznsbye.css';
import '../../css/r/rdlb1bc-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGyKKOiefb" x1="-376.827" x2="-271.043" y1="315.916" y2="437.861" gradientTransform="translate(1208.005 -831.793)scale(2.8346)" gradientUnits="userSpaceOnUse"><stop offset="0" class="b5gyd0c0a"/><stop offset="1" class="dlbznsbye"/></linearGradient><linearGradient id="SVGs4XuDd5R" x1="-376.557" x2="-271.302" y1="316.228" y2="437.563" gradientTransform="translate(1208.005 -831.793)scale(2.8346)" gradientUnits="userSpaceOnUse"><stop offset="0" class="b5gyd0c0a"/><stop offset="1" class="dlbznsbye"/></linearGradient><path fill="url(#SVGyKKOiefb)" stroke="url(#SVGs4XuDd5R)" class="rdlb1bc-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:obtainium" /></template>
