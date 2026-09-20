<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffo8hqbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ffo8hqbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:ticket" /></template>
