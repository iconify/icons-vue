<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3_f12b3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3_f12b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:movie-search-outline" /></template>
