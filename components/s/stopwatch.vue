<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-a8jubem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-a8jubem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:stopwatch" /></template>
