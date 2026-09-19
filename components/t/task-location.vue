<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7bj30f0q.css';
import '../../css/t/thj5gk-ag.css';
import '../../css/r/rututhb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="w7bj30f0q"/><path class="thj5gk-ag"/><path class="rututhb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:task-location" /></template>
