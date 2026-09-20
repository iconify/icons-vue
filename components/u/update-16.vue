<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-lm3x_hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a-lm3x_hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:update-16" /></template>
