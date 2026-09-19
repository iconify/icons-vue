<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmrrr4bud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pmrrr4bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:sparkle-stroke-16" /></template>
