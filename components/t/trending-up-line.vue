<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve27pm75g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve27pm75g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:trending-up-line" /></template>
