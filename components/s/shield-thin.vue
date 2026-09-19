<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljl08gbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljl08gbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:shield-thin" /></template>
