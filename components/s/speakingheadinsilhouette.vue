<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3y2h-bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r3y2h-bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:speakingheadinsilhouette" /></template>
