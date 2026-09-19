<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggts764pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggts764pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:restaurant" /></template>
