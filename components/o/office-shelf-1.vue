<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjjnd6bwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjjnd6bwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:office-shelf-1" /></template>
