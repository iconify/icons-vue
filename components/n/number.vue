<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfseh4bvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="bfseh4bvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:number" /></template>
