<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhjy0tbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jhjy0tbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shrimp-remix" /></template>
