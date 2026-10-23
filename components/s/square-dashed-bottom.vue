<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iebl_j8zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iebl_j8zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-dashed-bottom" /></template>
