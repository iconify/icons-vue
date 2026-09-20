<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etfx2dbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="etfx2dbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:trail-blazes-up" /></template>
