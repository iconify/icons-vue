<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/d2rk8jb9a.css';
import '../../css/q/qy3sbkj_s.css';
import '../../css/u/udxsowrax.css';
import '../../css/f/fnqqe5b5e.css';
import '../../css/c/c7xnwmbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="d2rk8jb9a wm-k"/><path class="qy3sbkj_s wm-a"/><path class="udxsowrax wm-shadow"/><path class="fnqqe5b5e wm-k"/><path class="c7xnwmbpp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:trash-engrave" /></template>
