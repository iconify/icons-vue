<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mplvu4bxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mplvu4bxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:stop" /></template>
