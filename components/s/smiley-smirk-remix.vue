<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6jggylob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y6jggylob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-smirk-remix" /></template>
