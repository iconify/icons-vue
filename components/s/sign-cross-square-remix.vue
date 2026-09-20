<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxq03j9uz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wxq03j9uz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:sign-cross-square-remix" /></template>
