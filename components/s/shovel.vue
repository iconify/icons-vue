<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shj9caboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="shj9caboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:shovel" /></template>
