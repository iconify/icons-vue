<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5citje1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="d5citje1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:radiobox-marked" /></template>
