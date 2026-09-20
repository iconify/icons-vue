<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdm8trd6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bdm8trd6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:speech-bubble-subtitles-solid" /></template>
