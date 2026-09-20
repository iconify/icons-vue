<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erj0l9c7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="erj0l9c7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sedan-under-wrench" /></template>
