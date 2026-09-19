<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd1z4ji4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd1z4ji4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:play-bar-two" /></template>
