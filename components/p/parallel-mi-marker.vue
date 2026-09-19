<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw70umb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<path class="hw70umb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:parallel-mi-marker" /></template>
