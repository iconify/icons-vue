<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-jd13bdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s-jd13bdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mountains" /></template>
