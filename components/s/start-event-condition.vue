<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb8trccfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jb8trccfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:start-event-condition" /></template>
