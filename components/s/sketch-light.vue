<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8ss29b8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r8ss29b8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sketch-light" /></template>
