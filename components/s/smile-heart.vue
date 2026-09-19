<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0q4cdc_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0q4cdc_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:smile-heart" /></template>
