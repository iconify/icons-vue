<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_2_1m9-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c_2_1m9-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:spoon-beside-table-knife-in-gable-roofed-shelter" /></template>
