<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru49qvb2s.css';
import '../../css/i/i6xqw31vr.css';
import '../../css/e/e_po1hivt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVG7e3avbKN" x1="13.9" x2="498.1" y1="256" y2="256" gradientUnits="userSpaceOnUse"><stop offset="0" class="ru49qvb2s"/><stop offset="1" class="i6xqw31vr"/></linearGradient><path fill="url(#SVG7e3avbKN)" class="e_po1hivt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trek" /></template>
