<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8qjfwb5z.css';
import '../../css/m/mjmo6o7rp.css';
import '../../css/t/tctv76bhi.css';
import '../../css/k/ksdryubwm.css';
import '../../css/s/s_dwlvbyp.css';
import '../../css/o/odwcfcbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVGY1gIvxZa" x2="1" y1="1"><stop offset="0" class="p8qjfwb5z"/><stop offset="1" class="mjmo6o7rp"/></linearGradient><linearGradient id="SVG1EmZ6bfy" x2="1" y1="1"><stop offset="0" class="tctv76bhi"/><stop offset="1" class="ksdryubwm"/></linearGradient></defs><path fill="url(#SVGY1gIvxZa)" class="s_dwlvbyp"/><path fill="url(#SVG1EmZ6bfy)" class="odwcfcbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:velite" /></template>
