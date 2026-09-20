<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq_olcclz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq_olcclz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:perl" /></template>
