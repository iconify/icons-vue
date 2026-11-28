<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udy-qb4uj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udy-qb4uj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:puzzle-check" /></template>
