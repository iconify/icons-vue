<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7n9xvbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r7n9xvbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rotate-counterclockwise-filled" /></template>
