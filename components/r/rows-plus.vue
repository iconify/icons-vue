<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn1a4jxpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn1a4jxpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:rows-plus" /></template>
