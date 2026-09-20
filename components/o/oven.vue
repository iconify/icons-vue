<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzup42osd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="tzup42osd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:oven" /></template>
