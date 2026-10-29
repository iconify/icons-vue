<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/a-k3z2s9a.css';
import '../../css/i/ifxccrbkd.css';
import '../../css/x/xsm6pfbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="a-k3z2s9a"/><path class="ifxccrbkd wm-k"/><path class="wm-a xsm6pfbut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:stocking-sketch" /></template>
