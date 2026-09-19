<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9yhs_54b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9yhs_54b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:objects-vertical-top" /></template>
