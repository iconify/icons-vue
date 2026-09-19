<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1i54mbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="q1i54mbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:path" /></template>
