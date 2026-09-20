<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy4hlac5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy4hlac5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-67-small" /></template>
