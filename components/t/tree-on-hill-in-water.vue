<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz4so0yad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gz4so0yad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tree-on-hill-in-water" /></template>
