<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_3yviq6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="x_3yviq6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:square-caret-left" /></template>
