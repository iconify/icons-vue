<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwr2e0b0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="jwr2e0b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:quote" /></template>
