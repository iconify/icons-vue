<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckt3eabti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckt3eabti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:scanner-bold" /></template>
