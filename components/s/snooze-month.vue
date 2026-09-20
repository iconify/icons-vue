<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edhu5n-ej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="edhu5n-ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:snooze-month" /></template>
