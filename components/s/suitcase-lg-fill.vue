<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9bav7b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t9bav7b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:suitcase-lg-fill" /></template>
