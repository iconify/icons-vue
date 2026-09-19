<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjd3gbc5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tjd3gbc5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:previous" /></template>
