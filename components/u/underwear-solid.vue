<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-7ab4_rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-7ab4_rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:underwear-solid" /></template>
