<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4_7t_bwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4_7t_bwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sorting-04" /></template>
