<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tabpkmb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tabpkmb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pill-tablet-outline" /></template>
