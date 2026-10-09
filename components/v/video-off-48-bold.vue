<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eihpo_wmr.css';
import '../../css/z/z32ck6l6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eihpo_wmr"/><path class="z32ck6l6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:video-off-48-bold" /></template>
