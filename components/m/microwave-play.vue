<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujd98nbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujd98nbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:microwave-play" /></template>
