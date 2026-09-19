<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-kti_wao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-kti_wao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:pills-bottle-1" /></template>
