<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8zl3bcns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8zl3bcns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:youtube-subscription" /></template>
