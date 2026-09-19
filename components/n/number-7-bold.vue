<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr_qs9ogj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr_qs9ogj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-7-bold" /></template>
