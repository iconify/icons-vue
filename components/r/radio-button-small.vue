<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2v5x-bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="u2v5x-bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:radio-button-small" /></template>
