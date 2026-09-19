<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylv12j38f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ylv12j38f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:square-minus" /></template>
