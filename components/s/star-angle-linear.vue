<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyopwhbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyopwhbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-angle-linear" /></template>
