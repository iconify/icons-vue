<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhefa7bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhefa7bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:skip-back-fill" /></template>
