<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uexrb2bpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uexrb2bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:restaurant-table" /></template>
