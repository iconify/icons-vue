<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfluhxliu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="qfluhxliu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:person-arrow-down-to-line" /></template>
