<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztt3ahbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztt3ahbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:wallet-x" /></template>
