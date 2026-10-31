<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/e/edp2z3bic.css';
import '../../css/l/l7rp9pspr.css';
import '../../css/k/kvenboveb.css';
import '../../css/y/yk6w4ldpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="edp2z3bic wm-shadow"/><path class="l7rp9pspr wm-shadow"/><path class="kvenboveb"/><path class="yk6w4ldpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:rolling-pin" /></template>
