<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvyku1b5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tvyku1b5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:plane-cruising-above-water" /></template>
