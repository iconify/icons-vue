<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owfdg3b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="owfdg3b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:shopping-box" /></template>
