<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcn09ub7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fcn09ub7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:nervous-face-in-circle" /></template>
