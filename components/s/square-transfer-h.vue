<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srm6rdpdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="srm6rdpdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-transfer-h" /></template>
