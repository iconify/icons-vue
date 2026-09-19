<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4dg4xj4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f4dg4xj4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:mute" /></template>
