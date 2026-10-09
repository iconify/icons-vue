<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaye-t6-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qaye-t6-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:parallelogram-20-bold" /></template>
