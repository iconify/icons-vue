<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2xgv55tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y2xgv55tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:no" /></template>
