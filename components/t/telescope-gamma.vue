<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z538v9b6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z538v9b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:telescope-gamma" /></template>
