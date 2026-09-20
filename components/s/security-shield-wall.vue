<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8eh7n5jh.css';
import '../../css/j/j7h15zsik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d8eh7n5jh"/><path class="j7h15zsik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:security-shield-wall" /></template>
