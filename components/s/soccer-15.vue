<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz9vejtvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uz9vejtvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:soccer-15" /></template>
