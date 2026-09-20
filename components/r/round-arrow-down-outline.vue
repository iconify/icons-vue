<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omu9mvuwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="omu9mvuwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-arrow-down-outline" /></template>
