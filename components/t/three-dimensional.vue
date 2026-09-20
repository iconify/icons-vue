<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6tse1upv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k6tse1upv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:three-dimensional" /></template>
