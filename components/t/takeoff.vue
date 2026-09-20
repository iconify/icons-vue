<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpkqq8beq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jpkqq8beq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:takeoff" /></template>
