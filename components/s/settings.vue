<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d94zbcb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d94zbcb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:settings" /></template>
