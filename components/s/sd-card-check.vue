<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcqu69boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcqu69boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:sd-card-check" /></template>
