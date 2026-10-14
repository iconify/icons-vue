<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1kbat3fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o1kbat3fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:polaris-game-streaming-light" /></template>
