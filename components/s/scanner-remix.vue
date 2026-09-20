<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn-z210wd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yn-z210wd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:scanner-remix" /></template>
