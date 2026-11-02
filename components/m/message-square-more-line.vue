<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rads5acki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rads5acki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-square-more-line" /></template>
