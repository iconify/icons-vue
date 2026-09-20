<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia7l2rsyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia7l2rsyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:medium" /></template>
