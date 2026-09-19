<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-v7-ebrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f-v7-ebrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:play-btn-fill" /></template>
