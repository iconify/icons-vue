<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghs2nbb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghs2nbb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:microsoft-teams" /></template>
