<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb3sy8b4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb3sy8b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:trademark-circle" /></template>
