<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v15m2hbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v15m2hbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:move" /></template>
