<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbhi0cbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sbhi0cbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:obsidian-dark" /></template>
