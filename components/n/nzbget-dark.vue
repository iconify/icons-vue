<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/del0unbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="del0unbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nzbget-dark" /></template>
