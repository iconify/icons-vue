<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao65_1bln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao65_1bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:shield-lock" /></template>
