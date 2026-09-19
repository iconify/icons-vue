<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb1kyut_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb1kyut_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:short-left" /></template>
