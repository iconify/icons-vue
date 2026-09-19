<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnsqrrbig.css';
import '../../css/f/f-af1wzga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nnsqrrbig"/><path class="f-af1wzga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:strawberry" /></template>
