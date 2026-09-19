<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de93w3jem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="de93w3jem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:translation-created-stroke-16" /></template>
