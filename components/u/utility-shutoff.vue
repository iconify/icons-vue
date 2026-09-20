<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q90m5qb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q90m5qb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:utility-shutoff" /></template>
