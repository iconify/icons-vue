<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6ljr9t_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="w6ljr9t_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:tab-panel" /></template>
