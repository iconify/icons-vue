<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l29605bwn.css';
import '../../css/u/ur2d1ktml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l29605bwn"/><path class="ur2d1ktml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:sun" /></template>
