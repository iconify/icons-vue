<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gaf1vx3va.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gaf1vx3va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:run-compact" /></template>
