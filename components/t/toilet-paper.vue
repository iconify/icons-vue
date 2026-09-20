<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpd9z7b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpd9z7b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:toilet-paper" /></template>
