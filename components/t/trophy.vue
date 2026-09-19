<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7rg5yowr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g7rg5yowr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:trophy" /></template>
