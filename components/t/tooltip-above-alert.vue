<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmf80-bpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="dmf80-bpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:tooltip-above-alert" /></template>
