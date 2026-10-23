<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsds0r5em.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsds0r5em"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:tree-deciduous" /></template>
