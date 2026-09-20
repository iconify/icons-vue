<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rngb50b_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rngb50b_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wrench-cog" /></template>
