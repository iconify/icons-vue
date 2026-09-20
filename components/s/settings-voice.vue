<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znsu68bzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znsu68bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:settings-voice" /></template>
