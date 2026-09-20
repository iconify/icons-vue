<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc1_vptuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cc1_vptuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:toilet-paper-solid" /></template>
