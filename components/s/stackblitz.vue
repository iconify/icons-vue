<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt7ggacqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gt7ggacqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:stackblitz" /></template>
