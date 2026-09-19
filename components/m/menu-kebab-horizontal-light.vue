<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcgi44bxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcgi44bxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:menu-kebab-horizontal-light" /></template>
