<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdcn7f_bq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdcn7f_bq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sigma-solid" /></template>
