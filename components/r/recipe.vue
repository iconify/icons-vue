<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0t096bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i0t096bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:recipe" /></template>
