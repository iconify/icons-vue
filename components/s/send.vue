<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i77b7xbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i77b7xbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:send" /></template>
