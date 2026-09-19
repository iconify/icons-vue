<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh-1a_bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh-1a_bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:star-dashed" /></template>
