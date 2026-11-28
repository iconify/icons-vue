<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6hr64b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6hr64b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:snowman" /></template>
