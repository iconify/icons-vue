<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fefl6abxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fefl6abxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:subtitles" /></template>
