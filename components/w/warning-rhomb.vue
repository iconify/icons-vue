<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffll-1b4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ffll-1b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:warning-rhomb" /></template>
