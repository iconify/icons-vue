<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihu8-ii_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihu8-ii_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:nigerian-naira" /></template>
