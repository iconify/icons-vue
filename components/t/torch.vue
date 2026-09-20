<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x86x4fbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="x86x4fbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:torch" /></template>
