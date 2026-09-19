<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thj720svm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="thj720svm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:tablet" /></template>
