<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfe806brr.css';
import '../../css/c/cngewyg-g.css';
import '../../css/e/ezlrtwd4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qfe806brr"/><path class="cngewyg-g"/><path class="ezlrtwd4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mediamanager" /></template>
