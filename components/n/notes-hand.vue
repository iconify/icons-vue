<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md8en7cla.css';
import '../../css/p/p1hqjib3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="md8en7cla"/><path class="p1hqjib3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:notes-hand" /></template>
