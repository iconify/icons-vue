<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6p_rxb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6p_rxb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:vertical-distribute-bottom" /></template>
