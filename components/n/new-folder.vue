<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0tui7bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="p0tui7bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:new-folder" /></template>
