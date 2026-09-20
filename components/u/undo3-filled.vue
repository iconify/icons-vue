<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so8gcqb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so8gcqb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:undo3-filled" /></template>
