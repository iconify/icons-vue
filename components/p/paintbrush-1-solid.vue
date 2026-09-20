<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flxjsl7sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="flxjsl7sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:paintbrush-1-solid" /></template>
