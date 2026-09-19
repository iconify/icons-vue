<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlkn-rbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<path class="rlkn-rbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:manual" /></template>
