<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd5imhbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dd5imhbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:moon" /></template>
