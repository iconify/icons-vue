<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kje457rsc.css';
import '../../css/c/ckdfspy3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kje457rsc"/><path class="ckdfspy3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:view-timeline" /></template>
