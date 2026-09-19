<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr5l7qb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr5l7qb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:window-sidebar" /></template>
