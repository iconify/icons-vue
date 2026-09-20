<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axj03hbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="axj03hbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:music-equalizer-flat" /></template>
