<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plyct1bun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plyct1bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:space" /></template>
