<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yszp-9b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yszp-9b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sandstorm-20-bold" /></template>
