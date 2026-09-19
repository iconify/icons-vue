<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8jkilbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8jkilbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wallshade" /></template>
