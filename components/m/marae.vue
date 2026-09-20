<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1_80_b6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d1_80_b6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:marae" /></template>
