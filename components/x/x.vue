<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgy1x0b6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xgy1x0b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:x" /></template>
