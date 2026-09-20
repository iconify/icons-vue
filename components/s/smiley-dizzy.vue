<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2jkth9an.css';
import '../../css/p/ph3npob9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2jkth9an"/><path class="ph3npob9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:smiley-dizzy" /></template>
