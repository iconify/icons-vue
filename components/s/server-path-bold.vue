<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txex11drz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="txex11drz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:server-path-bold" /></template>
