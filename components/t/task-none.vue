<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0028ibxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<path class="p0028ibxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:task-none" /></template>
