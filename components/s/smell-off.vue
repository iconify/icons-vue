<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4v_u2b7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4v_u2b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:smell-off" /></template>
