<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n43-wcaxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n43-wcaxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:minnesota-with-capital-star" /></template>
