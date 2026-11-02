<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy7mig5by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy7mig5by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-square-code-fill" /></template>
