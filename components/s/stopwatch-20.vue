<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr6a2-c4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="kr6a2-c4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:stopwatch-20" /></template>
