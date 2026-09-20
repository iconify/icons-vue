<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faz4r52oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="faz4r52oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:office-worker-remix" /></template>
