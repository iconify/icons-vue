<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1-eh7tkj.css';
import '../../css/j/jdu6zub5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1-eh7tkj"/><path clip-rule="evenodd" class="jdu6zub5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:plex" /></template>
