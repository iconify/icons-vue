<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jaxm-tbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jaxm-tbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-backward-square-30-line" /></template>
