<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io5j2zbie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io5j2zbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:webrtc" /></template>
