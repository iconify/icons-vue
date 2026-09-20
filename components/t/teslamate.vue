<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prptthbtt.css';
import '../../css/w/wu4g6i-qu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="prptthbtt"/><path class="wu4g6i-qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:teslamate" /></template>
