<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve2l6q1jt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ve2l6q1jt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:x" /></template>
