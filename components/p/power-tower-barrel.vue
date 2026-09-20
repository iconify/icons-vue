<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2nnlccyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l2nnlccyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:power-tower-barrel" /></template>
