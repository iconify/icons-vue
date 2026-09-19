<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c47y40d3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c47y40d3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tesla-fart" /></template>
