<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj-s7ache.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj-s7ache"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:trending-down-solid" /></template>
