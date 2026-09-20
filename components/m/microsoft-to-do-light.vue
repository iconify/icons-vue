<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6g9c7b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i6g9c7b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-to-do-light" /></template>
