<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsx9bkbtz.css';
import '../../css/b/bqcr30b7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jsx9bkbtz"/><path class="bqcr30b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:search-20" /></template>
