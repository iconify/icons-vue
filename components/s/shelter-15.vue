<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6h-xxbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x6h-xxbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:shelter-15" /></template>
