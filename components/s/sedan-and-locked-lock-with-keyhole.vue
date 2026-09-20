<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa2ykobom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wa2ykobom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sedan-and-locked-lock-with-keyhole" /></template>
