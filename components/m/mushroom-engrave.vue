<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gpzd8zb1s.css';
import '../../css/t/ts-fa3biy.css';
import '../../css/q/qf-tu6dot.css';
import '../../css/i/iycs7wjzl.css';
import '../../css/t/tsi5nvbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gpzd8zb1s wm-k"/><path class="ts-fa3biy wm-a"/><path class="qf-tu6dot wm-shadow"/><path class="iycs7wjzl wm-k"/><path class="tsi5nvbml wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mushroom-engrave" /></template>
