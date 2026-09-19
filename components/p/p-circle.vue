<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9duzibif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s9duzibif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:p-circle" /></template>
