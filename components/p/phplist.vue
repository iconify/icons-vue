<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znzw_sapr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":704};
const content = `<path class="znzw_sapr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:phplist" /></template>
