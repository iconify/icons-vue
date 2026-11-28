<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laol5_b3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="laol5_b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:wifi-x" /></template>
