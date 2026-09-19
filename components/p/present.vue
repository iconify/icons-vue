<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fne8_2cyb.css';
import '../../css/f/fb8tbxvyp.css';
import '../../css/b/bsys6tb1q.css';
import '../../css/b/bm17v2acr.css';
import '../../css/v/vbzbhtims.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fne8_2cyb"/><path class="fb8tbxvyp"/><path class="bsys6tb1q"/><path class="bm17v2acr"/><path class="vbzbhtims"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:present" /></template>
