<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9qbubbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9qbubbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:move-up-right" /></template>
