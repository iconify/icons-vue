<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkmi6bh9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nkmi6bh9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:subtitles" /></template>
