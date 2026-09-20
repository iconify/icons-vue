<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdq15rypm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sdq15rypm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:shard" /></template>
