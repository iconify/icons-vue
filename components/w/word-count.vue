<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qacb63tzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="qacb63tzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:word-count" /></template>
