<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl551cj4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hl551cj4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:south-dakota-with-capital-star" /></template>
