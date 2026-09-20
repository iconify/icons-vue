<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/senz_sbfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="senz_sbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wind-beaufort-0" /></template>
