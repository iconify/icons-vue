<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-b_tb_2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-b_tb_2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mega" /></template>
