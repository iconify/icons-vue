<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/ixv74mb6y.css';
import '../../css/c/cltoiebep.css';
import '../../css/t/t11v-vb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ixv74mb6y wm-k"/><path class="cltoiebep wm-k"/><path class="t11v-vb0a wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-sketch" /></template>
