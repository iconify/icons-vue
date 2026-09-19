<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsq0juwui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tsq0juwui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:shell" /></template>
