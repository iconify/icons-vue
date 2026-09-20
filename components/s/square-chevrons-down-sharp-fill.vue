<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktja0ebaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktja0ebaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-chevrons-down-sharp-fill" /></template>
