<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvz3e3b4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvz3e3b4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:redbubble" /></template>
