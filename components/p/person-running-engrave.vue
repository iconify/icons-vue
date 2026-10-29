<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hc3341b_i.css';
import '../../css/n/nmcr65isa.css';
import '../../css/s/sv9gucnbt.css';
import '../../css/v/vh1b5unvh.css';
import '../../css/z/z6enqggrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hc3341b_i wm-k"/><path class="nmcr65isa wm-a"/><path class="sv9gucnbt wm-shadow"/><path class="vh1b5unvh wm-k"/><path class="wm-a z6enqggrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:person-running-engrave" /></template>
