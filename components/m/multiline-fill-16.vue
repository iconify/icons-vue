<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt3r6j27x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kt3r6j27x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:multiline-fill-16" /></template>
