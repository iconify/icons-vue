<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf1evobxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf1evobxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stamp-fill-round" /></template>
