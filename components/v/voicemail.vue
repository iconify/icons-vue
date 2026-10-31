<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/a/amzs2vygw.css';
import '../../css/f/fgl7d3b2i.css';
import '../../css/q/qj2ybmbte.css';
import '../../css/u/uqwdcjxkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="amzs2vygw wm-shadow"/><path class="fgl7d3b2i wm-shadow"/><path class="qj2ybmbte"/><path class="uqwdcjxkk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:voicemail" /></template>
