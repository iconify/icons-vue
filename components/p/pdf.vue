<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohaf0s28w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohaf0s28w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pdf" /></template>
