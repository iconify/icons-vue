<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wivd8hhlh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wivd8hhlh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:vapi" /></template>
