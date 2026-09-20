<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pme8--b2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="pme8--b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:tooltip-start" /></template>
