<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dssqhxb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dssqhxb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-line-fill-round" /></template>
