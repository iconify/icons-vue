<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d23-cbbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d23-cbbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:medical-cross-check" /></template>
