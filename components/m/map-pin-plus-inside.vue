<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nba_ijb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nba_ijb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:map-pin-plus-inside" /></template>
