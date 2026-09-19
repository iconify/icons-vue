<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h69ttsb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h69ttsb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:voicemail" /></template>
