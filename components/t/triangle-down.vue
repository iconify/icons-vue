<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsdjueb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsdjueb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:triangle-down" /></template>
