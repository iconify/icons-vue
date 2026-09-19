<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3_vvgb0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":240,"height":700};
const content = `<path class="k3_vvgb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:select" /></template>
