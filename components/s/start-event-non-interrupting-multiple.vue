<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytmp8tbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ytmp8tbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:start-event-non-interrupting-multiple" /></template>
