<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpy244bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpy244bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:palette-plus" /></template>
