<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1t2ripgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r1t2ripgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:twitch-outline" /></template>
