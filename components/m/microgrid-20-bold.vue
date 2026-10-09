<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7588rxqu.css';
import '../../css/w/w97g-pbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j7588rxqu"/><path class="w97g-pbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:microgrid-20-bold" /></template>
