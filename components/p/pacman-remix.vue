<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6j3f6b2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e6j3f6b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pacman-remix" /></template>
