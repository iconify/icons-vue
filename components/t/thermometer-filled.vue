<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-0co0btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-0co0btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:thermometer-filled" /></template>
