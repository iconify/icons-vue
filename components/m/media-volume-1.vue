<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruey6ybuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ruey6ybuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-volume-1" /></template>
