<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suk0u9b4j.css';
import '../../css/o/o2vmq0bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="suk0u9b4j"/><path class="o2vmq0bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moon-crescent-20" /></template>
