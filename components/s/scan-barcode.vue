<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/u/ults33brt.css';
import '../../css/q/qsbi9kdry.css';
import '../../css/w/wgli4bboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="ults33brt wm-shadow"/><path class="qsbi9kdry wm-shadow"/><path class="wgli4bboz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:scan-barcode" /></template>
