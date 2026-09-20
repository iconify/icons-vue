<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux1onib1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux1onib1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:rss" /></template>
