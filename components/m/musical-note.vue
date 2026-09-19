<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iovxvlb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iovxvlb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:musical-note" /></template>
