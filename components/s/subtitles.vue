<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwe74tbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwe74tbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:subtitles" /></template>
