<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee-9a1ddt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee-9a1ddt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:star-outline" /></template>
