<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfwp-acbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rfwp-acbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:quality-education" /></template>
