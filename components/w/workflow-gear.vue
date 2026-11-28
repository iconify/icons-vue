<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlk9ttbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlk9ttbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:workflow-gear" /></template>
