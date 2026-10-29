<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/q/qxr4d-bhc.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/g/g56t_c8un.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="qxr4d-bhc wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="g56t_c8un"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:panel-bottom-blueprint" /></template>
