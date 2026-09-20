<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c61hf1_xg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c61hf1_xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:serverless" /></template>
