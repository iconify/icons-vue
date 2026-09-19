<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti3pf4j_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti3pf4j_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:slider-01" /></template>
