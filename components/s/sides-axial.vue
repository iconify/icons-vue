<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o155z10jr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="o155z10jr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:sides-axial" /></template>
