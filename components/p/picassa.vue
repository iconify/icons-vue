<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4y_u1bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":488};
const content = `<path class="r4y_u1bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:picassa" /></template>
