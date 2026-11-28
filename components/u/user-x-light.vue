<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4c8j9fyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="d4c8j9fyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:user-x-light" /></template>
