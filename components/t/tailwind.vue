<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbs6dzvcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rbs6dzvcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:tailwind" /></template>
