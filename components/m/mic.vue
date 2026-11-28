<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwjin0lcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwjin0lcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mic" /></template>
