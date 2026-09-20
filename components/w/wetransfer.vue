<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw_ptxbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw_ptxbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:wetransfer" /></template>
