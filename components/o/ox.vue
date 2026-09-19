<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e24zqdb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e24zqdb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:ox" /></template>
