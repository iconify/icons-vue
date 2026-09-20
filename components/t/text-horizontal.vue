<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7mckpelx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="k7mckpelx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:text-horizontal" /></template>
