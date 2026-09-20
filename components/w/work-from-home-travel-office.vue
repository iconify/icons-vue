<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtud3ynqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mtud3ynqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:work-from-home-travel-office" /></template>
