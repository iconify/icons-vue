<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t75kpmbuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t75kpmbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:zodiac-5-remix" /></template>
