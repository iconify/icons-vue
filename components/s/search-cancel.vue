<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1_t7obhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n1_t7obhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:search-cancel" /></template>
