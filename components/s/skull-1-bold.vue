<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9pdrvokh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9pdrvokh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:skull-1-bold" /></template>
