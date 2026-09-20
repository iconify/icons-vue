<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5ev77boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="u5ev77boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:scanner" /></template>
