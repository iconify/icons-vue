<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khirxibgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khirxibgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:nodejs-line" /></template>
