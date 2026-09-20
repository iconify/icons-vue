<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rknwa3bti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rknwa3bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:volleyball-15" /></template>
