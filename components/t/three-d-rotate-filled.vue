<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1bizmbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1bizmbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:three-d-rotate-filled" /></template>
