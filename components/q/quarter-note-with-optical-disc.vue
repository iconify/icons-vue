<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz152z8so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sz152z8so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:quarter-note-with-optical-disc" /></template>
