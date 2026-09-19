<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inb686g-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="inb686g-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:ruby" /></template>
