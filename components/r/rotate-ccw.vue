<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt_4kcc7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt_4kcc7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:rotate-ccw" /></template>
