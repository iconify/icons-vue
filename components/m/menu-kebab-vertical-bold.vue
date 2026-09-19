<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0ux_1vag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0ux_1vag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:menu-kebab-vertical-bold" /></template>
