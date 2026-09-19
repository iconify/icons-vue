<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rizcbgzbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rizcbgzbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:report" /></template>
