<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhxaa3bwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhxaa3bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:short-down" /></template>
