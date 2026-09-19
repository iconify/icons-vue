<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faoq3ykkk.css';
import '../../css/d/d28ipjbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="faoq3ykkk"/><path class="d28ipjbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:time-filled" /></template>
