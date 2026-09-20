<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7-sevcfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y7-sevcfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:sort-high-to-low-outline" /></template>
