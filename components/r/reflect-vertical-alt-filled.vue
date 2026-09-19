<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne5zp8bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ne5zp8bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:reflect-vertical-alt-filled" /></template>
