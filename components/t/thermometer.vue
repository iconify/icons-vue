<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt4i1t6ih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt4i1t6ih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:thermometer" /></template>
