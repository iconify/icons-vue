<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l_dr-jbem.css';
import '../../css/t/t2srnhboy.css';
import '../../css/s/svvk-3k2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="l_dr-jbem"/><path class="t2srnhboy wm-a"/><path class="svvk-3k2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:save-duo" /></template>
