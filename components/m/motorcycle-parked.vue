<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euksa8bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="euksa8bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:motorcycle-parked" /></template>
