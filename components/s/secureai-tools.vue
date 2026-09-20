<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qadmupuce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qadmupuce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:secureai-tools" /></template>
