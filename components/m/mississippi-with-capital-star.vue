<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa_2w9b_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qa_2w9b_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:mississippi-with-capital-star" /></template>
