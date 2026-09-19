<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do17ynreu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="do17ynreu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:warning-compact" /></template>
