<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_ja0lbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h_ja0lbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:ruff" /></template>
