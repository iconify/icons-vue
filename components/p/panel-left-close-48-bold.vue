<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9a09orqa.css';
import '../../css/e/ecr-u4bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q9a09orqa"/><path class="ecr-u4bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:panel-left-close-48-bold" /></template>
