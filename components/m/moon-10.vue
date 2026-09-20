<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih0mf8ell.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="ih0mf8ell"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-10" /></template>
