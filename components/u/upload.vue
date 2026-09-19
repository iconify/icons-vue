<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni8fv72nb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":32};
const content = `<path class="ni8fv72nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:upload" /></template>
