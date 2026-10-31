<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbrmk0bbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbrmk0bbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:utensils-fill-round" /></template>
