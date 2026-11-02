<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-jy4_bfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-jy4_bfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:to-do-fill" /></template>
