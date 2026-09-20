<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml3alvz3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml3alvz3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:view-module" /></template>
