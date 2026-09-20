<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioxie2bbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ioxie2bbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:ruler-remix" /></template>
