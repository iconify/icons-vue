<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8k4hxboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="u8k4hxboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:sonography" /></template>
