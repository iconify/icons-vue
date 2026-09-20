<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2iokcbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o2iokcbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:matrix-light" /></template>
