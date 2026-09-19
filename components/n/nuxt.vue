<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esbpl1bxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="esbpl1bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:nuxt" /></template>
