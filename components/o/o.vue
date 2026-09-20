<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr1_dtboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kr1_dtboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:o" /></template>
