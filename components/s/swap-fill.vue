<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3vv2btbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v3vv2btbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:swap-fill" /></template>
