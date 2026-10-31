<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw5w_lbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw5w_lbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tally-5-fill-round" /></template>
