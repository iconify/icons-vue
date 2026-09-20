<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb9h84b7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="bb9h84b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:tooltip-start-help" /></template>
