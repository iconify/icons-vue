<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev7zx5mob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev7zx5mob primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:wind-duotone" /></template>
