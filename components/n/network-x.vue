<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruwa10bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruwa10bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:network-x" /></template>
