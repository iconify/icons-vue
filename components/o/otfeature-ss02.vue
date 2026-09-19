<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob2r7obdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ob2r7obdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-ss02" /></template>
