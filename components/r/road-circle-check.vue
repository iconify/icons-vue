<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bag_e0a9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bag_e0a9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:road-circle-check" /></template>
