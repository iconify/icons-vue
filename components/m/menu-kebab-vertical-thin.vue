<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4pycz6mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4pycz6mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:menu-kebab-vertical-thin" /></template>
