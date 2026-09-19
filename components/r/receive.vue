<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9cngdc1l.css';
import '../../css/e/ew7188tnn.css';
import '../../css/b/blb99bcah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<g class="o9cngdc1l"><path class="ew7188tnn"/><path class="blb99bcah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:receive" /></template>
