<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo50atbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fo50atbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:signal-high-20-bold" /></template>
