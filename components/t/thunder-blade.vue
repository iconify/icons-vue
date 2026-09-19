<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2ghah3xq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h2ghah3xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:thunder-blade" /></template>
