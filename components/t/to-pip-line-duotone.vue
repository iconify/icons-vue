<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rtwy_gbxk.css';
import '../../css/x/xnh1ybbye.css';
import '../../css/y/yq3ukacfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rtwy_gbxk"/><path class="xnh1ybbye"/><path class="yq3ukacfg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:to-pip-line-duotone" /></template>
