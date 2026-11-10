<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy-3afbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vy-3afbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:plus-in-circle" /></template>
