<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnsw1bv8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnsw1bv8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:puzzle-plus" /></template>
