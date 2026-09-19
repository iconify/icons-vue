<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzktj7b9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nzktj7b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:mermaid" /></template>
