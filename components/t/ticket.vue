<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvvhqn41i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yvvhqn41i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:ticket" /></template>
