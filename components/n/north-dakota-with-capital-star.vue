<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyx2mnb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dyx2mnb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:north-dakota-with-capital-star" /></template>
