<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/d8dmb3bdn.css';
import '../../css/r/rnjr3mbxg.css';
import '../../css/j/j5ep5hbtz.css';
import '../../css/u/uc0yabbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="d8dmb3bdn wm-k"/><path class="rnjr3mbxg wm-shadow"/><path class="j5ep5hbtz wm-k"/><path class="uc0yabbtt wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scroll-text-engrave" /></template>
