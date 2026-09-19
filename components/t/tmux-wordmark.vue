<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/o/onao27b_c.css';
import '../../css/d/dmeb_lbay.css';
import '../../css/k/kr4h8my1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="bi12bsetm"><path class="onao27b_c"/><path class="dmeb_lbay"/><path class="kr4h8my1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:tmux-wordmark" /></template>
