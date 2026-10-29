<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/njkh7x6mj.css';
import '../../css/o/oy3jc5b_n.css';
import '../../css/a/ajhk2abxb.css';
import '../../css/f/f19ei9bez.css';
import '../../css/w/wfupqcc6c.css';
import '../../css/j/jd-9hyvzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="njkh7x6mj wm-k"/><path class="oy3jc5b_n wm-a"/><path class="ajhk2abxb wm-shadow"/><path class="f19ei9bez wm-k"/><path class="wfupqcc6c wm-a"/><path class="jd-9hyvzp wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:stroller-engrave" /></template>
