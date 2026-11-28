<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faloljb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="faloljb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tea-cup" /></template>
