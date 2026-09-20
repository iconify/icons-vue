<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emu812b6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="emu812b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:secrover-dark" /></template>
