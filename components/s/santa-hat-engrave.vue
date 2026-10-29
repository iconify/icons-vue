<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/toijuud3z.css';
import '../../css/f/fzuc9kcuc.css';
import '../../css/p/ph058rd7e.css';
import '../../css/f/fay72gbvh.css';
import '../../css/e/ef66r4bmf.css';
import '../../css/x/xu73cdcji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="toijuud3z wm-k"/><path class="fzuc9kcuc wm-a"/><path class="ph058rd7e wm-shadow"/><path class="fay72gbvh wm-k"/><path class="ef66r4bmf wm-k"/><path class="wm-a xu73cdcji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:santa-hat-engrave" /></template>
