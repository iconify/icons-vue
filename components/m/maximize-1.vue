<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m09wixb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m09wixb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:maximize-1" /></template>
