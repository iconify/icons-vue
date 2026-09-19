<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdh8ldc3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdh8ldc3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:menu-burger-horizontal-bold" /></template>
