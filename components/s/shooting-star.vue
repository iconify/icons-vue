<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwcr48b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwcr48b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:shooting-star" /></template>
