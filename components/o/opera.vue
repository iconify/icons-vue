<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzkjo4q4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzkjo4q4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:opera" /></template>
