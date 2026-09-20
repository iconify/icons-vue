<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsx5tmbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jsx5tmbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-burger-with-cheese-on-bun" /></template>
