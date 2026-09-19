<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug24mu6ni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ug24mu6ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:shop" /></template>
