<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5teifb3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j5teifb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:run-errors" /></template>
