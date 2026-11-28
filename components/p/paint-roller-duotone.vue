<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0njegbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0njegbyf primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:paint-roller-duotone" /></template>
