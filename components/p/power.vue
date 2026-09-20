<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6zlonm3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x6zlonm3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:power" /></template>
