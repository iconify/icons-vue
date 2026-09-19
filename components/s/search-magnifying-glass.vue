<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lord4lpuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lord4lpuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:search-magnifying-glass" /></template>
