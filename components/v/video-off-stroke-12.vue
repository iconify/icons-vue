<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgzc5-b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="tgzc5-b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:video-off-stroke-12" /></template>
