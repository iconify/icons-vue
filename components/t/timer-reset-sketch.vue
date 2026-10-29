<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/ditlfwbca.css';
import '../../css/m/mdy835mid.css';
import '../../css/j/jxj7b8bfj.css';
import '../../css/e/e7lab5bim.css';
import '../../css/l/lca_kabbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ditlfwbca"/><path class="mdy835mid wm-k"/><path class="jxj7b8bfj wm-a"/><path class="e7lab5bim wm-k"/><path class="lca_kabbu wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:timer-reset-sketch" /></template>
