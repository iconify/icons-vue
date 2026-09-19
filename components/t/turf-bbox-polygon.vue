<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqs9uef3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="yqs9uef3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="geo:turf-bbox-polygon" /></template>
