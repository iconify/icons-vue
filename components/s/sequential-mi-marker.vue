<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg1q73zov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<path class="zg1q73zov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:sequential-mi-marker" /></template>
