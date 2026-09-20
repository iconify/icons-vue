<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfg_v3xsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfg_v3xsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:omada-cloud" /></template>
