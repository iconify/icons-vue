<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te2je-_dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="te2je-_dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:v-card" /></template>
