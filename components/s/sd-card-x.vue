<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nibvr2bvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nibvr2bvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:sd-card-x" /></template>
