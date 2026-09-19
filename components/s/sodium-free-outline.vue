<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xujsi_bui.css';
import '../../css/g/gp92iuk-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="xujsi_bui"/><path clip-rule="evenodd" class="gp92iuk-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:sodium-free-outline" /></template>
