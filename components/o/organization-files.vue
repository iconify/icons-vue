<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt51gkbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rt51gkbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:organization-files" /></template>
