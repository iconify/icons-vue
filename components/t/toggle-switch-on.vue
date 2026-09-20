<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1-r7x1oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="f1-r7x1oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:toggle-switch-on" /></template>
