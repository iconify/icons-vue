<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv8i4385h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="pv8i4385h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:radio-button" /></template>
