<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkrl-8bgb.css';
import '../../css/g/g8ydabckk.css';
import '../../css/m/m35k5sbte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zkrl-8bgb"/><path class="g8ydabckk"/><path class="m35k5sbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:postiz" /></template>
