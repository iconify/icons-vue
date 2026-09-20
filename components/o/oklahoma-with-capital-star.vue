<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbomxmbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qbomxmbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:oklahoma-with-capital-star" /></template>
