<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-x6w3ngg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":51.974,"height":20.409,"left":-0.578,"top":-0.578};
const content = `<path class="m-x6w3ngg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ola-cabs" /></template>
