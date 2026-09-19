<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6q3yrbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="j6q3yrbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:page-facing-up-filled" /></template>
