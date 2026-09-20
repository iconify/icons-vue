<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vndv6hz4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vndv6hz4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ukca" /></template>
