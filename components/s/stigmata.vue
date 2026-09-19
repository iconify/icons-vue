<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfecfcb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rfecfcb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stigmata" /></template>
