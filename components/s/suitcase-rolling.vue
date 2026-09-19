<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqnz8m81q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="mqnz8m81q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:suitcase-rolling" /></template>
