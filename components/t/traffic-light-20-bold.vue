<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og5fw-c9e.css';
import '../../css/b/b16yxabjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="og5fw-c9e"/><path class="b16yxabjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:traffic-light-20-bold" /></template>
