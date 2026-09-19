<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfo7-6c4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="yfo7-6c4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:pencil" /></template>
