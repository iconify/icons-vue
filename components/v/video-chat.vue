<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdzywacwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="gdzywacwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:video-chat" /></template>
