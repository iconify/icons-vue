<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxew7j2zh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxew7j2zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:rime" /></template>
