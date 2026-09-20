<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd4x_8b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="rd4x_8b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:mention" /></template>
