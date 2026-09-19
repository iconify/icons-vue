<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7xb6qbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="e7xb6qbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:zoom-in-small" /></template>
