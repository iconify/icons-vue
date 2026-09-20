<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mey40abvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mey40abvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:text-style" /></template>
