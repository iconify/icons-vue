<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjfqldkyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qjfqldkyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:speech-bubble-inactive-expressive" /></template>
