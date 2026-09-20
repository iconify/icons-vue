<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/istztdwyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="istztdwyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:opera" /></template>
