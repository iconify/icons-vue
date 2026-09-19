<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trvxt9qye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="trvxt9qye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:question-lg" /></template>
