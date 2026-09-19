<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7yff5b2a.css';
import '../../css/i/i0e1ugb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<g transform="translate(0 995.638)"><path class="u7yff5b2a"/><rect class="i0e1ugb7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:subprocess-collapsed" /></template>
