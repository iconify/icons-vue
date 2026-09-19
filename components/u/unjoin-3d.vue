<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmh1iue4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmh1iue4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:unjoin-3d" /></template>
