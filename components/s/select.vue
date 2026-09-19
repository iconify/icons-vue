<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5yd4l70j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5yd4l70j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:select" /></template>
