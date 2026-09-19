<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4l1f8bgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e4l1f8bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:pantheon" /></template>
