<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm6c7eb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nm6c7eb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:stop-1" /></template>
