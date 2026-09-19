<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujmfz-dyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujmfz-dyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:vite-js" /></template>
