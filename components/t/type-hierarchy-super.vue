<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2yiggbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s2yiggbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:type-hierarchy-super" /></template>
