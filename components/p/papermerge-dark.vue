<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/ximi_9bwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ximi_9bwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:papermerge-dark" /></template>
