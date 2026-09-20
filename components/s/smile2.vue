<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpps04-hx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dpps04-hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:smile2" /></template>
