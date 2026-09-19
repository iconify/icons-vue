<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qacjvq_4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qacjvq_4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:unity" /></template>
