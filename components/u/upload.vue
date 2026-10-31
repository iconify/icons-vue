<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/i/i3eprdb7h.css';
import '../../css/z/zdmlo7ael.css';
import '../../css/o/ox649ehdc.css';
import '../../css/k/kmg-puiou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="i3eprdb7h wm-shadow"/><path class="wm-shadow zdmlo7ael"/><path class="ox649ehdc"/><path class="kmg-puiou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:upload" /></template>
