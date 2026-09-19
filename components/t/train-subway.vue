<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o39d96b_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="o39d96b_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:train-subway" /></template>
