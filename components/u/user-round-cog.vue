<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2puoha2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2puoha2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user-round-cog" /></template>
