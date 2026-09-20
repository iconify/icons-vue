<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct297rbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ct297rbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:turnkey-linux" /></template>
