<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbzrglgab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dbzrglgab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shovel-rake-remix" /></template>
