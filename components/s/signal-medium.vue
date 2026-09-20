<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0y0d0byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0y0d0byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:signal-medium" /></template>
