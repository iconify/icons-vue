<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwbbkcc-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xwbbkcc-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:phone-call-speaker-stroke-12" /></template>
