<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9h0xjb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="e9h0xjb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:partly-cloudy-day" /></template>
