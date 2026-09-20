<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2p6chu2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="z2p6chu2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-alt-waning-crescent-2" /></template>
