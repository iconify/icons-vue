<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kljtf455q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="kljtf455q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:width" /></template>
