<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkw6nm7zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkw6nm7zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:map-exclamation" /></template>
