<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp2wuju4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp2wuju4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tag-chevron-fill" /></template>
