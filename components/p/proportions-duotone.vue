<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q050sk4js.css';
import '../../css/y/yhx8xobnk.css';
import '../../css/u/uu_td6bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q050sk4js"/><path class="yhx8xobnk"/><path class="uu_td6bkc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:proportions-duotone" /></template>
