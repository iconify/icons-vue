<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w14ao9mev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w14ao9mev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:stairs-up-arrow" /></template>
