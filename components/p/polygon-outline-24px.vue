<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdhb58bwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mdhb58bwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:polygon-outline-24px" /></template>
