<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxj7stbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxj7stbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:terminal-fill" /></template>
