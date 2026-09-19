<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa71y1b3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa71y1b3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:triangle-flag" /></template>
