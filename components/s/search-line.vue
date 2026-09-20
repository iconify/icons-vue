<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep-je_kdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep-je_kdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:search-line" /></template>
