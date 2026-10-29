<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/g4f78b0_e.css';
import '../../css/c/cfuirvnhg.css';
import '../../css/k/k3qcgxbnp.css';
import '../../css/b/buxga7syi.css';
import '../../css/x/xqt6rxbmt.css';
import '../../css/e/elf7rzb6q.css';
import '../../css/o/ozmt8_9qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="g4f78b0_e wm-k"/><path class="cfuirvnhg wm-a"/><path class="k3qcgxbnp wm-shadow"/><path class="buxga7syi wm-k"/><path class="wm-a xqt6rxbmt"/><path class="elf7rzb6q wm-s"/><path class="ozmt8_9qw wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:red-envelope-engrave" /></template>
