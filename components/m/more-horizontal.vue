<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/u9jxybcpr.css';
import '../../css/x/xs7xanrwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="u9jxybcpr"/><path vector-effect="non-scaling-stroke" class="xs7xanrwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:more-horizontal" /></template>
