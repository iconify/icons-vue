<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg501v9yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eg501v9yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:section-remove-outline" /></template>
