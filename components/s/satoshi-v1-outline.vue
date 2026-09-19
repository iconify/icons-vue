<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sibgfifdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sibgfifdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:satoshi-v1-outline" /></template>
