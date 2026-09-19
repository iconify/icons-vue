<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vml1vdbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vml1vdbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:symbol-field" /></template>
