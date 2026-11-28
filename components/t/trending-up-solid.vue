<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogqe36bjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogqe36bjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:trending-up-solid" /></template>
