<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbynv2bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="pbynv2bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:paint-bucket" /></template>
