<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riarkacif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="riarkacif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:pinterest" /></template>
