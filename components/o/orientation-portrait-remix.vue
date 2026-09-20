<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2hrrr2gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z2hrrr2gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:orientation-portrait-remix" /></template>
