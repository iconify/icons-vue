<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faz80ofhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="faz80ofhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:ventilation" /></template>
