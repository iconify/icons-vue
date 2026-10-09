<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3_ihpb5f.css';
import '../../css/d/d3xqtkb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e3_ihpb5f"/><path class="d3xqtkb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rotate-cw-20-bold" /></template>
