<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw9gdt5eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bw9gdt5eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:step-backward-solid" /></template>
