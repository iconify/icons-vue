<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5s43x33f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l5s43x33f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:thatched-roof-hut" /></template>
