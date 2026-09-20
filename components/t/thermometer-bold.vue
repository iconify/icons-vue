<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziks3bbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ziks3bbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:thermometer-bold" /></template>
