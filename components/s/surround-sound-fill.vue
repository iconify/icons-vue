<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgppzacoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgppzacoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:surround-sound-fill" /></template>
