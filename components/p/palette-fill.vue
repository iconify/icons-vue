<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl18oebpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl18oebpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:palette-fill" /></template>
