<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5s51sblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t5s51sblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:maximize-square-bold" /></template>
