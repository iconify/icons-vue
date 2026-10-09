<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnkuq4b8x.css';
import '../../css/t/tz4q3ccfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cnkuq4b8x"/><path class="tz4q3ccfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:toaster-20-bold" /></template>
