<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh4rs-bkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gh4rs-bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:video-subtitles-remix" /></template>
