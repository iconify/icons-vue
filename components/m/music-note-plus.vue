<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6sjh55au.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6sjh55au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:music-note-plus" /></template>
