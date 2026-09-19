<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0zqk9bjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v0zqk9bjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:strikethrough" /></template>
