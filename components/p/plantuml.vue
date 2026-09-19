<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el8e7murg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="el8e7murg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:plantuml" /></template>
