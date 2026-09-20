<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/a446cjlod.css';
import '../../css/n/nxszfactq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path vector-effect="non-scaling-stroke" class="a446cjlod"/><path vector-effect="non-scaling-stroke" class="nxszfactq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:navigation-overlay" /></template>
