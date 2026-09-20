<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9zfdl87i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="i9zfdl87i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:tooltip-above-help" /></template>
