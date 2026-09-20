<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_hr8qb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_hr8qb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:search-globe" /></template>
