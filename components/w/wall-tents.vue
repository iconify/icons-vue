<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8kv29e8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e8kv29e8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wall-tents" /></template>
