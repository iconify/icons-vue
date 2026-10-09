<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvh-2kb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vvh-2kb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:square-dashed-48" /></template>
