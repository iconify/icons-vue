<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjmq40opm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jjmq40opm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:seo-eye-network" /></template>
