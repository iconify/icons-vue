<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/y7lwahbyc.css';
import '../../css/q/qynj9glqj.css';
import '../../css/b/b55os-lyu.css';
import '../../css/b/bkk0xnbka.css';
import '../../css/l/l4ok05b1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k y7lwahbyc"/><path class="qynj9glqj wm-shadow"/><path class="b55os-lyu wm-k"/><path class="bkk0xnbka wm-k"/><path class="l4ok05b1o wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:newspaper-engrave" /></template>
