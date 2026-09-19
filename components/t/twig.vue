<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnk6u5eey.css';
import '../../css/s/sd_7wj8_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nnk6u5eey"/><path class="sd_7wj8_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:twig" /></template>
