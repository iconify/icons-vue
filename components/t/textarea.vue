<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf_i67yps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sf_i67yps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:textarea" /></template>
