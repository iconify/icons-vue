<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq7t5p63g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sq7t5p63g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:scarf" /></template>
