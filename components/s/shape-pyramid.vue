<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du2s2hbvi.css';
import '../../css/p/p6bj_kbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="du2s2hbvi"/><path class="p6bj_kbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:shape-pyramid" /></template>
