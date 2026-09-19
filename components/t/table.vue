<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8utzgnxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l8utzgnxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:table" /></template>
