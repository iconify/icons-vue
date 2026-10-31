<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvi71bchf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvi71bchf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:map-pin-gloss" /></template>
