<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c230y1g7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c230y1g7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:undo" /></template>
