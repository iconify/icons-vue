<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aub60qb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aub60qb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:scissors-cut-fill" /></template>
