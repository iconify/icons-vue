<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/l/lu9u9u8wt.css';
import '../../css/q/qf7tbcbyb.css';
import '../../css/j/ju8v6k8zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lu9u9u8wt"/><path class="qf7tbcbyb"/><path class="ju8v6k8zc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:triangle-alert-sharp" /></template>
