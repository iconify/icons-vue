<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs77xgrwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xs77xgrwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:nav-arrow-up" /></template>
