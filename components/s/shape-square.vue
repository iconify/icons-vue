<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psybx4g9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psybx4g9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:shape-square" /></template>
