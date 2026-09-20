<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv3_1acnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv3_1acnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:money-alt" /></template>
