<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-5d3-a9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-5d3-a9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:window-grid" /></template>
