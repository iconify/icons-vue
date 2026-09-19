<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkd8ybcyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkd8ybcyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:messanger" /></template>
