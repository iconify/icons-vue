<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyhe3ob7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eyhe3ob7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:volume-muted-stroke-16" /></template>
