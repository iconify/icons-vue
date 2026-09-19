<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agjshx11i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="agjshx11i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:prettier-ignore" /></template>
