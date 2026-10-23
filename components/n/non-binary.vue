<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u91f8-bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u91f8-bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:non-binary" /></template>
