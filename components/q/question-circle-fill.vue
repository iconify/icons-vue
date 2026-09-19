<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2_f5cb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k2_f5cb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:question-circle-fill" /></template>
