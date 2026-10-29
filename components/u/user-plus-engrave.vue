<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/djiqt-b-p.css';
import '../../css/p/p5vicub1t.css';
import '../../css/g/gkf0wyr6p.css';
import '../../css/e/emha3wbqe.css';
import '../../css/f/f86q_5yiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="djiqt-b-p wm-k"/><path class="p5vicub1t wm-s"/><path class="gkf0wyr6p wm-shadow"/><path class="emha3wbqe wm-k"/><path class="f86q_5yiw wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-plus-engrave" /></template>
