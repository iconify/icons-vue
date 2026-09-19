<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4io5yi0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w4io5yi0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:panda-css" /></template>
