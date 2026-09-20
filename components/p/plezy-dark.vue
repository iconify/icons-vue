<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy9_b6x2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qy9_b6x2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plezy-dark" /></template>
