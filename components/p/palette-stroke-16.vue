<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvu7g3cfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xvu7g3cfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:palette-stroke-16" /></template>
