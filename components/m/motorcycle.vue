<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn8e2rbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="xn8e2rbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:motorcycle" /></template>
