<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnh7u9f3r.css';
import '../../css/v/vo3vedbmo.css';
import '../../css/g/gfjx0h0sh.css';
import '../../css/c/cxs370dyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gnh7u9f3r"/><g class="vo3vedbmo"><path transform="matrix(.79989 0 0 .79796 .1 -.697)" class="gfjx0h0sh"/><path transform="matrix(.79989 0 0 .79796 .1 -.697)" class="cxs370dyl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:rust-config" /></template>
