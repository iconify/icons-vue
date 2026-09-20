<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-_punbps.css';
import '../../css/q/q8b3x8beh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h-_punbps"/><path class="q8b3x8beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:rotate-clockwise-16" /></template>
