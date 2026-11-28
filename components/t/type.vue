<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm2opabqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm2opabqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:type" /></template>
