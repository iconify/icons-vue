<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgso04boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cgso04boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:two-dot-vertical-line-in-rectangle" /></template>
