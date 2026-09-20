<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oysdye0wl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oysdye0wl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-subtitles" /></template>
