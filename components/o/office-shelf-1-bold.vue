<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h156wkdle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h156wkdle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:office-shelf-1-bold" /></template>
