<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq4y6eb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq4y6eb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:text-box-check" /></template>
