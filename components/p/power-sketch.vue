<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jrl639bzb.css';
import '../../css/c/cqn-6lboc.css';
import '../../css/g/g_wmz4e_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jrl639bzb"/><path class="cqn-6lboc wm-k"/><path class="g_wmz4e_j wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:power-sketch" /></template>
