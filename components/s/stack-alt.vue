<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-qq7fbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l-qq7fbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:stack-alt" /></template>
