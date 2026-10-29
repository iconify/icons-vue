<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/o3jg7nbdr.css';
import '../../css/v/vhq7hmbdn.css';
import '../../css/q/qsg1dubrj.css';
import '../../css/n/n8ihr8b9o.css';
import '../../css/c/c8st50gyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="o3jg7nbdr wm-k"/><path class="vhq7hmbdn wm-s"/><path class="qsg1dubrj wm-shadow"/><path class="n8ihr8b9o wm-k"/><path class="c8st50gyo wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:phone-outgoing-engrave" /></template>
