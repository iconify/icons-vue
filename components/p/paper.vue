<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doooacb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":39,"height":39};
const content = `<path class="doooacb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:paper" /></template>
