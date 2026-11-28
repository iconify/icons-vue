<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruo-o8h7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruo-o8h7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:podcast-play" /></template>
