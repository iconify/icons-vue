<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i49v73y4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i49v73y4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:mobile-phone-camera-remix" /></template>
