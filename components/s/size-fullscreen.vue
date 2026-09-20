<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8ktb-bmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u8ktb-bmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:size-fullscreen" /></template>
