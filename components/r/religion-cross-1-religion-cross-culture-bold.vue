<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osu97bcqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="osu97bcqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:religion-cross-1-religion-cross-culture-bold" /></template>
