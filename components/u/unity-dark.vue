<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6hgihjwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":263};
const content = `<path class="o6hgihjwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:unity-dark" /></template>
