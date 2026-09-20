<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yct52e2ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yct52e2ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:smashing-magazine" /></template>
