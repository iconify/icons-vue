<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls6_xn_4i.css';
import '../../css/s/ss60qzbvo.css';
import '../../css/z/zlms2bb-e.css';
import '../../css/j/j_hdszcam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ls6_xn_4i"><path class="ss60qzbvo"/><path class="zlms2bb-e"/><path class="j_hdszcam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:stylelint" /></template>
