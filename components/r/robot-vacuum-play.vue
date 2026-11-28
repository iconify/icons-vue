<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw8qjxovw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw8qjxovw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:robot-vacuum-play" /></template>
