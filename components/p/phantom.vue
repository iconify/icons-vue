<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrza40bty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrza40bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:phantom" /></template>
