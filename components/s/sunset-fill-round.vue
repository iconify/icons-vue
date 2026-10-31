<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz10ehb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz10ehb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sunset-fill-round" /></template>
