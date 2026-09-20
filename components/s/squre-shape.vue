<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mll5hmbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="mll5hmbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:squre-shape" /></template>
