<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/l/lsdvd3b4y.css';
import '../../css/h/hhb5cob6b.css';
import '../../css/g/gh5712bfx.css';
import '../../css/q/qhdit6mxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="lsdvd3b4y wm-shadow"/><path class="hhb5cob6b wm-shadow"/><path class="gh5712bfx"/><path class="qhdit6mxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:network" /></template>
