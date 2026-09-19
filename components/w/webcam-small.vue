<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6jpl60lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="y6jpl60lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:webcam-small" /></template>
