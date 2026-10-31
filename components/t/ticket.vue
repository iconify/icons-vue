<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/m/mmco1-hig.css';
import '../../css/f/fai59idpe.css';
import '../../css/w/wofxy3bdj.css';
import '../../css/y/yefoqdcpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="mmco1-hig wm-shadow"/><path class="fai59idpe wm-shadow"/><path class="wofxy3bdj"/><path class="yefoqdcpc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:ticket" /></template>
