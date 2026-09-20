<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhf0vfbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yhf0vfbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:music-tone" /></template>
