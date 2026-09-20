<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak85jub6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ak85jub6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:node" /></template>
