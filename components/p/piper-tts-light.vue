<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_p8v1b3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x_p8v1b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:piper-tts-light" /></template>
