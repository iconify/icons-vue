<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg4m7ypgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="gg4m7ypgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:recurring-task" /></template>
