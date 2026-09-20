<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gomhksbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="gomhksbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:table-top-door-vertical" /></template>
