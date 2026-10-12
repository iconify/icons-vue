<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4-hwxpky.css';
import '../../css/w/wtf96pb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c4-hwxpky"/><path class="wtf96pb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:microphone-off-stroke-20" /></template>
