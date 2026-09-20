<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la915559x.css';
import '../../css/b/b7desccca.css';
import '../../css/l/l67011rfc.css';
import '../../css/u/umyps621i.css';
import '../../css/l/ll65juqtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":224,"height":80,"left":36,"top":112};
const content = `<defs><linearGradient id="SVGG9quWdvO" x1="191.65" x2="250" y1="133.58" y2="133.58" gradientUnits="userSpaceOnUse"><stop offset="0" class="la915559x"/><stop offset="1" class="b7desccca"/></linearGradient></defs><path class="l67011rfc"/><path fill="url(#SVGG9quWdvO)" class="umyps621i"/><path class="ll65juqtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mir-dark" /></template>
