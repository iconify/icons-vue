<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azayl7bty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azayl7bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:utensils-knife" /></template>
