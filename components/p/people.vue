<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-bjm8byo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y-bjm8byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:people" /></template>
