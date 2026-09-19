<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmdz1kbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cmdz1kbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:steering-wheel" /></template>
