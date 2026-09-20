<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moizcky5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="moizcky5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trello-light" /></template>
