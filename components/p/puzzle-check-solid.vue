<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym7_kkb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ym7_kkb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:puzzle-check-solid" /></template>
