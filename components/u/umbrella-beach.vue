<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1q3mddfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1q3mddfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:umbrella-beach" /></template>
