<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts6bgccjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ts6bgccjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spa-stones-20" /></template>
