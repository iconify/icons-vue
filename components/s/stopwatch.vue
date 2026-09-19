<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv2u20usj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mv2u20usj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:stopwatch" /></template>
