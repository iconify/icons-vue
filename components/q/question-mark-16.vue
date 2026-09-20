<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziybv1boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ziybv1boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:question-mark-16" /></template>
