<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajpwr3bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajpwr3bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:move-expand-vertical" /></template>
