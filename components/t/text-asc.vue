<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov2t5ibwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="ov2t5ibwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:text-asc" /></template>
