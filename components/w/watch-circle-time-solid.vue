<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vot7kibza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vot7kibza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:watch-circle-time-solid" /></template>
