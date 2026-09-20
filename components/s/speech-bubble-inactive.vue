<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8n8jh6bk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x8n8jh6bk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:speech-bubble-inactive" /></template>
