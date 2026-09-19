<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd-xe713w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rd-xe713w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:vuvuzelas" /></template>
