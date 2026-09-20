<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do2dhcc6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="do2dhcc6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-very-shocked-remix" /></template>
