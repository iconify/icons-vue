<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk8qblmxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xk8qblmxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wall-hanging-with-mountains-and-sun" /></template>
