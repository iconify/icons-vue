<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruyn-vy-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ruyn-vy-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorcycle-under-wrench" /></template>
