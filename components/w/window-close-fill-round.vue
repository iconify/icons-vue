<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i91yb9t8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i91yb9t8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-close-fill-round" /></template>
