<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju7fwpb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="ju7fwpb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:w3c" /></template>
