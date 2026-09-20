<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yix277b5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yix277b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shoe-formal" /></template>
