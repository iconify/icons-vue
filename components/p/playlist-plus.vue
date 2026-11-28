<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp7ogdeoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp7ogdeoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:playlist-plus" /></template>
