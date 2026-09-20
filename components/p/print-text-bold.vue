<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbccqd-dr.css';
import '../../css/y/y_4cj2byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbccqd-dr"/><path class="y_4cj2byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:print-text-bold" /></template>
