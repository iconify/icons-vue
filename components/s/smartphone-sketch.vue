<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/z66tkfv3t.css';
import '../../css/t/tbhozsb4v.css';
import '../../css/c/ccaydnkju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="z66tkfv3t"/><path class="tbhozsb4v wm-k"/><path class="ccaydnkju wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:smartphone-sketch" /></template>
