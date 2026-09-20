<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqxvh-bno.css';
import '../../css/j/jheje3btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wqxvh-bno"/><path class="jheje3btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:video-movies-set-equipment" /></template>
