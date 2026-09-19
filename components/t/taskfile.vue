<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eewmafs7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eewmafs7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:taskfile" /></template>
