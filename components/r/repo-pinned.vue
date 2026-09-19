<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fif97fbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fif97fbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:repo-pinned" /></template>
