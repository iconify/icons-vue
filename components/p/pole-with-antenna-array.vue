<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzn8h_vqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rzn8h_vqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pole-with-antenna-array" /></template>
