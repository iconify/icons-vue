<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2lrzab-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p2lrzab-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:prison" /></template>
