<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-bkk4bwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p-bkk4bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:terminal-cli-fill-16" /></template>
