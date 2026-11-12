<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4sp8rbzj.css';
import '../../css/h/hn_12bbbv.css';
import '../../css/o/oq606cbun.css';
import '../../css/i/i9f1c8b7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGYOg36bMA" x1="445.6" x2="445.6" y1="45.8" y2="394.6" gradientUnits="userSpaceOnUse"><stop offset="0" class="h4sp8rbzj"/><stop offset="1" class="hn_12bbbv"/></linearGradient><path fill="url(#SVGYOg36bMA)" class="oq606cbun"/><linearGradient id="SVGwkqSQdBX" x1="255.9" x2="255.9" y1="45.8" y2="394.6" gradientUnits="userSpaceOnUse"><stop offset="0" class="h4sp8rbzj"/><stop offset="1" class="hn_12bbbv"/></linearGradient><path fill="url(#SVGwkqSQdBX)" class="i9f1c8b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:polaris" /></template>
