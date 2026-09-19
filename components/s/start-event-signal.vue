<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cixp7rbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="cixp7rbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:start-event-signal" /></template>
